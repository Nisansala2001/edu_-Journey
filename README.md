# Edu Journey

Edu Journey is an educational social platform designed to help students share their academic experiences, recommended resources, and life guides. The platform enables users to create posts with descriptions, up to three images, and a 10-second video clip. Other users can view, like, share, and refer to the mentioned resources.

## Features

- **User Authentication & Authorization**: Sign-up, login, and log-out with secure JWT-based authentication.
- **Post Management**: Create, update, delete, and retrieve posts with images, videos, and descriptions.
- **Interaction with Posts**: Like, comment, and follow posts and users, with real-time updates.
- **User Profile Management**: Users can create, update, and delete their profiles and posts.
- **Notification Management**: Get notified of likes, comments, and shares on your posts.
  
## Technology Stack

- **Backend**: Java (Spring Boot) - RESTful API
- **Frontend**: React.js
- **Authentication**: JWT-based Authentication
- **Database**: MySQL

## API Endpoints

- **Post Management**: 
  - `POST /api/posts`: Create a new post
  - `GET /api/posts`: Get all posts
  - `GET /api/posts/:postId`: Get a post by ID
  - `PUT /api/posts/:postId`: Update a post
  - `DELETE /api/posts/:postId`: Delete a post

- **Interaction Management**: 
  - Like, share, and comment on posts
  - Edit or delete comments

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/edu-journey.git
# edu_-Journey
