﻿

# Movie Library

## Overview

This is a movie library web application with user authentication, movie search, and movie list creation features. Users can create public or private lists of their favorite movies.

## Features

- User Authentication (Sign In/Sign Up)
- Search for movies using the OMDB API
- Create, view, and manage movie lists
- Public and private lists

## Tech Stack

- Frontend: React, React Router, Axios, CSS
- Backend: Node.js, Express, MongoDB, Mongoose
- Authentication: JWT
- Hosting: Vercel

## Installation

### Backend

1. Clone the repository
2. Navigate to the `backend` directory
3. Install dependencies: `npm install`
4. Create a `.env` file and add the following:
   ```
   MONGO_URI=<your_mongo_uri>
   JWT_SECRET=<your_jwt_secret>
   OMDB_API_KEY=<your_omdb_api_key>
   ```
5. Start the server: `npm start`

### Frontendww

1. Navigate to the `frontend` directory
2. Install dependencies: `npm install`
3. Create a `.env` file and add the following:
   ```
   REACT_APP_API_URL=<your_backend_api_url>
   ```
4. Start the development server: `npm start`

## Deployment

- Deploy the backend to Heroku
- Deploy the frontend to Vercel

## Usage

1. Register and login to the application
2. Search for movies using the search bar
3. Create new movie lists and add movies to them
4. View and manage your movie lists

## Demo

- Live Demo: [link to live demo]

## License

This project is licensed under the MIT License.
