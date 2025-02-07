# Social-Network-API
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Description

This project is a social network API built using Node.js, Express.js, and MongoDB. It allows users to share their thoughts, react to friends' thoughts, and manage their friend list.


## Installation

1. Clone the repository:
    
    git clone https://github.com/terrencethe1/Social-Network-API.git
    
2. Navigate to the project directory:
    
    cd Social-Network-API
    
3. Install the dependencies:
    
    npm install
    

## Usage

1. Start the server:
    
    npm start
    
2.  APIThe will be running on `http://localhost:3001`.

### User Routes

- `GET /api/users` - Get all users
- `GET /api/users/:userId` - Get a single user by ID
- `POST /api/users` - Create a new user
- `PUT /api/users/:userId` - Update a user by ID
- `DELETE /api/users/:userId` - Delete a user by ID
- `POST /api/users/:userId/friends/:friendId` - Add a friend
- `DELETE /api/users/:userId/friends/:friendId` - Remove a friend

### Thought Routes

- `GET /api/thoughts` - Get all thoughts
- `GET /api/thoughts/:thoughtId` - Get a single thought by ID
- `POST /api/thoughts` - Create a new thought
- `PUT /api/thoughts/:thoughtId` - Update a thought by ID
- `DELETE /api/thoughts/:thoughtId` - Delete a thought by ID
- `POST /api/thoughts/:thoughtId/reactions` - Add a reaction to a thought
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId` - Remove a reaction from a thought

## License

This project is licensed under the MIT License. 

Demo:
https://drive.google.com/file/d/1467qZwb0P7SjsPwIH6DJnxyEFlbp8jD2/view?usp=sharing
