# Movie App

This is a movie discovery application built with Expo and React Native. It uses the [The Movie Database (TMDb)](https://www.themoviedb.org/) API to fetch movie data.

## Features

- Discover popular movies.
- Search for movies.
- View movie details.
- Save movies to your profile (requires Appwrite configuration).

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [TMDB API Key](https://www.themoviedb.org/documentation/api)

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/movie-app.git
   cd movie-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root of the project and add your TMDB API key:

   ```
   EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
   ```

4. **Start the development server:**

   ```bash
   npx expo start
   ```

   This will open the Expo DevTools in your browser. You can then run the app on:

   - An Android emulator or device.
   - An iOS simulator or device.
   - In your web browser.

## Appwrite (Optional)

This project includes optional integration with [Appwrite](https://appwrite.io/) for user authentication and saving movies. To use these features, you will need to:

1. **Set up an Appwrite project.**
2. **Configure the following environment variables in your `.env` file:**

   ```
   EXPO_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
   EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
   ```

3. **Configure the Appwrite services in `services/appwrite.ts`.**

## Learn More

To learn more about the technologies used in this project, see the following resources:

- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/docs)
- [NativeWind Documentation](https://www.nativewind.dev/)
- [TMDb API Documentation](https://www.themoviedb.org/documentation/api)
- [Appwrite Documentation](https://appwrite.io/docs)
