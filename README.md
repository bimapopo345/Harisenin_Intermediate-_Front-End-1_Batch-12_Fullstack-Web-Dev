# Movie App

Movie App is a Fullstack web application that allows users to browse movies and TV shows, view details, and add items to their watchlist. The app utilizes The Movie Database (TMDb) API for fetching data and Firebase for authentication and storing user watchlists.

## About

The Movie App is built using React, with a custom UI theme designed using Chakra UI. It features a responsive design, allowing for a seamless user experience across various devices. The app's core functionality includes:

* Browsing trending movies and TV shows
* Viewing detailed information about each item, including cast, videos, and user ratings
* Adding items to a personal watchlist
* Authentication using Google Sign-In

## Features

* **Trending Page**: Displays a list of trending movies and TV shows, with the option to filter by time window (day or week)
* **Details Page**: Provides detailed information about a specific movie or TV show, including cast, videos, and user ratings
* **Watchlist Page**: Allows users to view and manage their personal watchlist, with the option to add or remove items
* **Search Functionality**: Enables users to search for specific movies or TV shows
* **Authentication**: Users can log in using Google Sign-In, and their watchlist is stored in Firebase

## Technology Stack

### Backend

* **Firebase**: Used for authentication and storing user watchlists
* **TMDb API**: Utilized for fetching movie and TV show data

### Frontend

* **React**: JavaScript library used for building the user interface
* **Chakra UI**: Custom UI theme designed using Chakra UI
* **Vite**: Development server and build tool

### Other Tools

* **Axios**: Used for making API requests to TMDb API
* **Firebase SDK**: Used for interacting with Firebase services

## Prerequisites

* **Node.js**: Installed on your system
* **npm** or **pnpm**: Package manager installed on your system
* **Vite**: Installed globally on your system (`npm install -g vite` or `pnpm install -g vite`)

## Installation

```bash
# Clone the repository
git clone <repository-url>
cd movie-app

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

1. Start the development server using `npm run dev` or `pnpm dev`.
2. Open your web browser and navigate to `http://localhost:3000`.
3. Browse the trending page, search for movies or TV shows, and view details.
4. Log in using Google Sign-In to access your personal watchlist.
5. Add or remove items from your watchlist.

## API Documentation

The Movie App uses the TMDb API for fetching data. You can find the API documentation [here](https://developers.themoviedb.org/3/getting-started/introduction).

## Deployment Instructions

To deploy the Movie App, you can use a service like Vercel or Netlify. Here's an example of how to deploy using Vercel:

```bash
# Create a Vercel account and install the Vercel CLI
npm install -g vercel

# Link your Vercel account to your project
vercel login

# Deploy your project
vercel
```

## Contributing Guidelines

To contribute to the Movie App, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Open a pull request against the main branch.

## License

The Movie App is licensed under the MIT License.

## Contact/Support Information

If you have any questions or need support, please contact the maintainers at [insert contact email or link to support page].
