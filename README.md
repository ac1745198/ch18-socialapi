Social Network API

This repository contains the code for a social network API built using Express.js and MongoDB with the Mongoose ODM.
Overview

The social network API allows users to:

    Register and authenticate.
    Share thoughts.
    React to friends' thoughts.
    Create and manage friend lists.

Technologies Used

    Node.js
    Express.js
    MongoDB
    Mongoose

Installation

    Clone this repository:

    bash

git clone <repository_url>

Install dependencies:

bash

cd social-network-api
npm install

Set up environment variables:

Create a .env file in the root directory and add the following variables:

makefile

    PORT=<port_number>
    MONGODB_URI=<mongodb_connection_uri>
    SECRET=<your_secret_key>

Usage

    Start the server:

    bash

    npm start

    Use API endpoints to interact with the social network.

API Endpoints

    POST /api/users/register: Register a new user.
    POST /api/users/login: Login an existing user.
    GET /api/users/:userId: Get user details.
    POST /api/thoughts: Create a new thought.
    GET /api/thoughts/:thoughtId: Get a specific thought.
    PUT /api/thoughts/:thoughtId: Update a thought.
    DELETE /api/thoughts/:thoughtId: Delete a thought.
    POST /api/thoughts/:thoughtId/reactions: Add a reaction to a thought.
    DELETE /api/thoughts/:thoughtId/reactions/:reactionId: Remove a reaction from a thought.
    POST /api/friends/:friendId: Add a friend.
    DELETE /api/friends/:friendId: Remove a friend.

Walkthrough Video

Please refer to the walkthrough video here.
Acknowledgments

    This project is part of the course curriculum.
    Thanks to the instructors for their guidance.

License

This project is licensed under the MIT License - see the LICENSE file for details.