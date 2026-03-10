# Seoul Place Recommendation Web

A web-based recommendation system that helps users explore places to visit in Seoul.
The platform allows users to select a district and receive curated recommendations for places to visit, including attractions, cultural spaces, and exhibitions.

The goal of this project is to provide an intuitive way for users to discover activities and locations within Seoul through a map-based interface.

---
### Overview

Finding places to visit in Seoul often requires searching across multiple platforms.
Many recommendations focus only on widely known “hot places,” while it can be difficult to explore diverse locations within a specific area.

This project aims to provide a simple interface where users can:
* Select a district in Seoul
* Explore recommended places within that district
* Discover attractions and cultural spaces such as exhibitions and performances
* View location information through a map-based interface

By organizing information by location and category, the platform makes it easier for users to discover things to do in Seoul.

---
### Features

* **District-based exploration**
  * Users can select a district (Gu) in Seoul.
* **Place recommendation**
  * The system provides recommended locations within the selected district.
* **Cultural activity information**
  * Users can browse places such as attractions, cultural spaces, and exhibitions.
* **Map-based interface**
  * Location data is visualized using the Kakao Maps API.
 
---
### System Architecture

The project consists of a simple frontend–backend architecture.

**Frontend**

React / React Router / Kakao Maps API


**Backend**

Node.js / Express

The frontend communicates with the backend through API requests to retrieve place and content information.

---
### Project Structure
```
Recommendation-System-for-Seoul
│
├── public
│   └── index.html          # Base HTML file
│
├── src
│   ├── App.js              # Main React application
│   ├── index.js            # Entry point
│   ├── data.js             # API request logic
│   └── components          # UI components
│
├── server.js               # Express backend server
├── package.json
```
