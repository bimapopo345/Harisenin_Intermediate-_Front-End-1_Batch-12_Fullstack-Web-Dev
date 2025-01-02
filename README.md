# Movie App
A full-stack web application for discovering and managing movies and TV shows.

## About
Movie App is a web application built using React, Vite, and Firebase. It allows users to discover new movies and TV shows, view details, and manage their watchlist. The application uses The Movie Database (TMDb) API for fetching data and Firebase for authentication and data storage.

## Features
* Discover trending movies and TV shows
* View details of movies and TV shows
* Manage watchlist
* Search for movies and TV shows
* Authentication using Google

## Technology Stack
### Backend
* Firebase Authentication
* Firebase Firestore

### Frontend
* React
* Vite
* Chakra UI

### Other Tools
* The Movie Database (TMDb) API

## Prerequisites
* Node.js (14 or higher)
* npm (6 or higher)
* Vite (3 or higher)
* Firebase account

## Installation
```bash
# Clone the repository
git clone https://github.com/bimapopo345/Harisenin_Intermediate-_Front-End-1_Batch-12_Fullstack-Web-Dev.git

# Change into the project directory
cd Harisenin_Intermediate-_Front-End-1_Batch-12_Fullstack-Web-Dev

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

## Environment Variables
```env
VITE_API_KEY=your_tmdb_api_key
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
```

## Usage Guide
1. Start the development server using `npm run dev` or `pnpm dev`.
2. Open the application in a web browser at `http://localhost:5173`.
3. Discover trending movies and TV shows on the homepage.
4. View details of movies and TV shows by clicking on the cards.
5. Manage your watchlist by adding or removing movies and TV shows.
6. Search for movies and TV shows using the search bar.

## API Documentation
The Movie Database (TMDb) API is used for fetching data. Please refer to the [TMDb API documentation](https://developers.themoviedb.org/3) for more information.

## Deployment Instructions
To deploy the application, follow these steps:
1. Build the application using `npm run build` or `pnpm build`.
2. Deploy the built application to a hosting platform such as Vercel or Netlify.
3. Configure the environment variables on the hosting platform.

## Contributing Guidelines
To contribute to the project, follow these steps:
1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix.
3. Make changes to the code and commit them.
4. Open a pull request on GitHub.

## License
The project is licensed under the MIT License.

## Contact/Support Information
For any questions or issues, please contact the maintainer at [bimapopo345@gmail.com](mailto:bimapopo345@gmail.com).
