# React Movie List

This project is a movie listing application built with React and Vite. It allows users to search for movies, view popular movies, and add movies to their favorites list.

## Features

- **Search Movies**: Users can search for movies using the search bar.
- **Popular Movies**: Displays a list of popular movies.
- **Favorites**: Users can add movies to their favorites list and view them on the favorites page.
- **Responsive Design**: The application is responsive and works well on different screen sizes.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A build tool that provides a fast development environment.
- **The Movie Database (TMDb) API**: Used to fetch movie data.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
   cd YOUR_REPOSITORY_NAME
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add your TMDb API key:
   ```env
   REACT_APP_TMDB_API_KEY=your_api_key_here
   ```

### Running the Application

To start the development server, run:

```sh
npm run dev
```

The application will be available at `http://localhost:3000`.

### Building for Production

To build the application for production, run:

```sh
npm run build
```

The production-ready files will be in the `dist` directory.

### Linting

To lint the code, run:

```sh
npm run lint
```

## Project Structure

```
frontend/
├── public/
├── src/
│   ├── components/
│   │   ├── NavBar.jsx
│   │   ├── MovieCard.jsx
│   ├── contexts/
│   │   ├── MovieContext.jsx
│   ├── css/
│   │   ├── App.css
│   │   ├── Favorites.css
│   │   ├── Home.css
│   │   ├── index.css
│   │   ├── MovieCard.css
│   │   ├── Navbar.css
│   ├── Pages/
│   │   ├── Favorites.jsx
│   │   ├── Home.jsx
│   ├── services/
│   │   ├── api.js
│   ├── App.jsx
│   ├── main.jsx
├── .gitignore
├── package.json
├── README.md
├── vite.config.js
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Note

This project was done for learning purposes.
