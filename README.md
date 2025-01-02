# Movie App
## Overview

The Movie App is a full-stack web application built with React, Vite, and Firebase. It allows users to browse and search for movies and TV shows, view details, and add items to their watchlist.

## Features and Benefits

*   Browse and search for movies and TV shows
*   View details, including cast, videos, and user ratings
*   Add items to a personalized watchlist
*   User authentication with Google Sign-In
*   Responsive design for a seamless user experience across devices

## Target Audience

The Movie App is designed for film enthusiasts and casual viewers alike, providing an easy-to-use platform for discovering and exploring movies and TV shows.

## Technology Highlights

*   Frontend: React, Vite, Chakra UI
*   Backend: Firebase Realtime Database, Firebase Authentication
*   APIs: The Movie Database (TMDb) API

## Table of Contents

*   [About](#about)
*   [Features](#features)
*   [Technology Stack](#technology-stack)
*   [Prerequisites](#prerequisites)
*   [Installation](#installation)
*   [Usage](#usage)
*   [API Documentation](#api-documentation)
*   [Deployment](#deployment)
*   [Contributing](#contributing)
*   [License](#license)
*   [Contact](#contact)

## Features and Functionality

*   **Browse and Search**: Browse trending movies and TV shows, or search for specific titles
*   **Details**: View detailed information about movies and TV shows, including cast, videos, and user ratings
*   **Watchlist**: Add items to a personalized watchlist for easy access
*   **User Authentication**: Sign in with Google to access watchlist and other features

## Technology Stack

### Backend

*   **Firebase Realtime Database**: NoSQL database for storing user data and watchlists
*   **Firebase Authentication**: User authentication with Google Sign-In

### Frontend

*   **React**: JavaScript library for building user interfaces
*   **Vite**: Development server and build tool
*   **Chakra UI**: UI component library

### APIs

*   **The Movie Database (TMDb) API**: API for retrieving movie and TV show data

## Prerequisites

*   Node.js (version 14 or higher)
*   npm (version 6 or higher) or pnpm (version 6 or higher)

## Installation

1.  Clone the repository: `git clone https://github.com/bimapopo345/bimapopo345-Harisenin_Intermediate-_Front-End-1_Batch-12_Fullstack-Web-Dev.git`
2.  Install dependencies:
    ```bash
npm install
```
    or
    ```bash
pnpm install
```
3.  Create a `.env` file in the root directory with the following environment variables:
    *   `VITE_API_KEY`: TMDb API key
    *   `VITE_FIREBASE_API_KEY`: Firebase API key
    *   `VITE_FIREBASE_AUTH_DOMAIN`: Firebase authentication domain
    *   `VITE_FIREBASE_PROJECT_ID`: Firebase project ID
    *   `VITE_FIREBASE_STORAGE_BUCKET`: Firebase storage bucket
    *   `VITE_FIREBASE_MESSAGING_SENDER_ID`: Firebase messaging sender ID
    *   `VITE_FIREBASE_APP_ID`: Firebase app ID

## Usage

1.  Start the development server:
    ```bash
npm run dev
```
    or
    ```bash
pnpm run dev
```
2.  Open the app in a web browser: `http://localhost:3000`

## API Documentation

The Movie App uses the TMDb API to retrieve movie and TV show data. Refer to the [TMDb API documentation](https://developers.themoviedb.org/3/getting-started/introduction) for more information.

## Deployment

To deploy the app, run the following command:
```bash
npm run build
```
or
```bash
pnpm run build
```
This will create a production-ready build in the `dist` directory.

## Contributing

Contributions are welcome! To contribute, please fork the repository and submit a pull request with your changes.

## License

The Movie App is licensed under the MIT License.

## Contact

For questions or issues, please contact the maintainer at [bimapopo345@gmail.com](mailto:bimapopo345@gmail.com).
