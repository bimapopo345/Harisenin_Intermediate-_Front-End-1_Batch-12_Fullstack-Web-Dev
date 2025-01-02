# CHILL MOVIE: A Movie and TV Show Database App
CHILL MOVIE is a full-stack web application that allows users to browse and search for movies and TV shows, view details, and manage a personal watchlist. The app utilizes the TMDb API for data and Firebase for authentication and database storage.

## Description
CHILL MOVIE is designed to provide an intuitive and user-friendly interface for discovering new movies and TV shows. The app features a home page that displays trending content, as well as dedicated pages for movies and TV shows. Users can search for specific titles, view detailed information, and add items to their watchlist.

## Key Features and Benefits
* **Trending Content**: View the latest trending movies and TV shows
* **Search**: Find specific titles using the search bar
* **Detailed Information**: View cast, crew, and other details for each title
* **Watchlist**: Add and manage titles in a personal watchlist
* **User Authentication**: Login with Google to access watchlist features

## Target Audience
CHILL MOVIE is designed for movie and TV show enthusiasts who want to discover new titles and manage their personal watchlist.

## Technology Highlights
* **Frontend**: Built using React, Chakra UI, and Vite
* **Backend**: Utilizes Firebase for authentication and database storage
* **API**: The TMDb API for movie and TV show data

## Table of Contents
- [About](#about)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features and Functionality
* Trending content display
* Search bar for finding specific titles
* Detailed information pages for movies and TV shows
* Personal watchlist management
* User authentication with Google

## Technology Stack
### Backend
* Firebase (authentication and database storage)
### Frontend
* React (JavaScript library for building user interfaces)
* Chakra UI (UI component library)
* Vite (build tool)
### Other Tools
* TMDb API (movie and TV show data)
* Google Authentication (user authentication)

## Prerequisites
* Node.js (for running the application)
* npm or pnpm (for package management)
* A Firebase project (for authentication and database storage)
* A TMDb API key (for accessing movie and TV show data)

## Installation
```bash
# Clone the repository
git clone <repository-url>
cd chill-movie

# Install dependencies
npm install
# or using pnpm
pnpm install

# Set up environment variables
cp .env.example .env

# Start development server
npm run dev
# or using pnpm
pnpm dev
```

## Usage
1. Open the application in your web browser at `http://localhost:3000`.
2. Browse trending content, search for specific titles, and view detailed information.
3. Login with Google to access watchlist features.
4. Add and manage titles in your personal watchlist.

## API Documentation
The TMDb API is used for accessing movie and TV show data. For more information, please refer to the [TMDb API documentation](https://www.themoviedb.org/documentation/api).

## Deployment
To deploy the application, you can use a service like Vercel or Netlify. Make sure to set up environment variables and configure the deployment settings according to your needs.

## Contributing
Contributions are welcome! To contribute, please fork the repository, make your changes, and submit a pull request.

## License
CHILL MOVIE is licensed under the MIT License.

## Contact
For any questions or issues, please contact the maintainers at [insert contact information].
