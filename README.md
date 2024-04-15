# CityBook Backend API

## Overview
CityBook Backend API is a Node.js and Express application interfacing with MongoDB. It's designed to handle CRUD operations for a city-based social application.

## Features
- CRUD operations for posts.

- Express server setup.
- MongoDB database integration with Mongoose.
- CORS enabled for cross-origin resource sharing.

## Installation
- Clone the repository.
- Run `npm install` to install dependencies.
- Set up `.env` file with `PORT` and `MONGODB_URI`.

## Usage
- Start the server with `npm start` or `node server.js`.
- Access the API on the defined PORT (default 4000).

## API Endpoints
- `POST /CityBook`: Create a new post.
- `GET /CityBook`: Get all posts.
- `DELETE /CityBook/:id`: Delete a post by ID.
- `PUT /CityBook/:id`: Update a post by ID.

## License
[State the project license or write 'Not specified'.]



