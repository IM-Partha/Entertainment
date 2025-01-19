# Entertainment App

The Entertainment App is a full-stack application designed to provide users with access to a vast collection of movies and TV shows, leveraging the TMDB API for fetching media details. It features user authentication, media exploration, and personal bookmarks, offering a comprehensive and personalized media browsing experience.

## Deployment
- **Frontend**: [Visit Frontend](https://entertainment-app-partha.vercel.app/)
- **Backend**: [Visit Backend](https://entertainment-web-app-0aqb.onrender.com/)

## Features
- **User Authentication**: Utilizes JWT for secure login and registration, ensuring user data protection.
- **Media Exploration**: Discover trending movies and TV shows with detailed views for each media item.
- **Bookmarks**: Bookmark favorite media for a personalized list of favorites.
- **Detailed Media Information**: Access in-depth details about movies and TV shows, including cast, genres, ratings, and more.

## Prerequisites
- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB instance (local or remote)
- TMDB API key for fetching media data

## Getting Started

### Backend Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/entertainment-app.git
   cd entertainment-web-app/backend
   npm install
##Configure Environment Variables: Create a .env file based on the provided .env.example file. Provide your MongoDB URI and TMDB API key in the .env file.

MONGODB_URL= "Mongodb connection string our url "
TOKEN= "Secret token for authentication & cookies"
NODE_ENV="Current environment - Development or Production"
TMDB_KEY="TMDB api key "
FRONTEND_URL="Frontend url"
Start the Server: Run the backend server.
    
