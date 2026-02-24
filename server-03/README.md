#  State Statistics Management API

A full REST API built using **Node.js** and **Express.js** to manage state statistics using an in-memory JSON database.

Supports **GET, POST, PUT, PATCH, DELETE** operations.

---

💫GitHub Repo:
https://github.com/Het-Roy/server-assignment/tree/main/server-02

💫Postman Documentation:
https://documenter.getpostman.com/view/50871368/2sBXcGCeTS

💫Render Deployment:
https://server-assignment-2-7bee.onrender.com/

---

##  Features

### GET Routes
- Get all states → `GET /states`
- Get state by ID → `GET /states/:id`
- Get state with highest GDP → `GET /states/highest-gdp`

### POST Route
- Add new state → `POST /states`

### PUT Routes
- Update state → `PUT /states/:id`
- Update budget → `PUT /states/:id/budget`
- Update population → `PUT /states/:id/population`

### PATCH Routes
- Update literacy → `PATCH /states/:id/literacy`
- Update GDP → `PATCH /states/:id/gdp`
- Update area → `PATCH /states/:id/area`

### DELETE Routes
- Delete state → `DELETE /states/:id`
- Delete by state name → `DELETE /states/name/:stateName`
- Delete states below literacy % → `DELETE /states/literacy/:percentage`