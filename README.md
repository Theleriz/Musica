# musica

project alike spotify but for free 
---

## General Overview
The project consists of three parts:

User side – frontend

Server side – auth-service, music-service

The frontend, auth-service, and music-service are implemented as microservices.
---
## Tech Stack
Frontend: HTML, CSS, JavaScript, React

Auth-service: C#, ASP.NET Core, PostgreSQL

Music-service: Java (frameworks for this microservice are not yet determined)
---
## Microservice Responsibilities
Frontend: The user-facing part of the web application

Auth-service: Handles user registration and authentication, stores user data in the database (login, password, etc.)

Music-service: Provides music streaming functionality, enables creation and management of user playlists, and supports music uploads