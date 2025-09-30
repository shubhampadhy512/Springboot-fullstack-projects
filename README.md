Project Overview

This backend manages disaster alerts and calculates safe evacuation routes.
It provides RESTful APIs to serve data to the frontend application.

Features

Manage disaster alerts (create, update, delete, fetch)

Calculate evacuation routes based on user location

Store and retrieve data from a database

RESTful APIs for frontend integration

API Endpoints (Examples)

GET /alerts – Fetch all disaster alerts

POST /alerts – Create a new disaster alert

GET /routes?start={lat,long}&end={lat,long} – Get evacuation route

GET /alerts/{id} – Fetch a specific alert

PUT /alerts/{id} – Update alert

DELETE /alerts/{id} – Delete alert

Future Enhancements

Connect backend to frontend for full-stack functionality

Add user authentication and roles

Integrate real-time disaster APIs

Push notifications for disaster alerts
