# Chill Movie App
A full-stack web application for discovering and watching movies and TV shows.

## About
Chill Movie App is a web application that allows users to discover new movies and TV shows, watch trailers, and add items to their watchlist. The application uses The Movie Database (TMDb) API for fetching data and Firebase for authentication and storing user data.

## Description
The application has the following features:
* Discover movies and TV shows by popularity, top rated, or search
* Watch trailers and videos
* Add items to watchlist
* View details of movies and TV shows, including cast, crew, and reviews
* User authentication using Google

## Features and Functionality
* **Discover Page**: Displays a list of trending movies and TV shows
* **Details Page**: Displays detailed information about a movie or TV show, including cast, crew, and reviews
* **Watchlist Page**: Displays a list of items added to the user's watchlist
* **Search Page**: Allows users to search for movies and TV shows
* **Authentication**: Users can login using Google authentication

## Technology Stack
### Backend
* **Firebase**: Used for authentication and storing user data
* **The Movie Database (TMDb) API**: Used for fetching data about movies and TV shows

### Frontend
* **React**: Used for building the user interface
* **Chakra UI**: Used for styling and layout
* **React Router**: Used for client-side routing

### Other Tools
* **Vite**: Used for building and serving the application
* **ESLint**: Used for code linting and formatting

## Prerequisites
* Node.js installed on the system
* Firebase account and project set up
* TMDb API key

## Installation
```bash
# Clone the repository
git clone <repository-url>
cd chill-movie-app

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

## Usage Guide
1. Start the development server by running `npm run dev` or `pnpm dev`
2. Open the application in a web browser at `http://localhost:3000`
3. Login using Google authentication
4. Explore the application and discover new movies and TV shows

## API Documentation
The TMDb API is used for fetching data about movies and TV shows. The API documentation can be found at [https://developers.themoviedb.org/3/getting-started/introduction](https://developers.themoviedb.org/3/getting-started/introduction)

## Deployment Instructions
1. Build the application by running `npm run build` or `pnpm build`
2. Deploy the built application to a hosting platform such as Vercel or Netlify

## Contributing Guidelines
Contributions are welcome! To contribute to the project, please follow these steps:
1. Fork the repository
2. Make changes and commit them
3. Create a pull request

## License
The project is licensed under the MIT License.

## Contact/Support Information
For any questions or issues, please contact the developer at [mailto:example@example.com](mailto:example@example.com)

## Table of Contents
- [About](#about)
- [Features](#features-and-functionality)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [API Documentation](#api-documentation)
- [Deployment](#deployment-instructions)
- [Contributing](#contributing-guidelines)
- [License](#license)
- [Contact](#contact/support-information)
