# Movie List

## Overview

Movie List is a React application that fetches popular movies from the TMDB API, enables users to search for movies, and allows them to add or remove movies from their favorites list. The app uses React Router for navigation and the Context API for managing state, with favorites persisted in localStorage.

## Features

- **Popular Movies:** Fetch and display popular movies.
- **Search:** Search movies by title.
- **Favorites:** Add or remove movies from a persistent favorites list.
- **Responsive UI:** Styled using custom CSS.
- **Modern Tooling:** Built with React and Vite for fast development.

## Installation

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AdnanSattar/movie-list.git
   cd movie-list
   ```

### Install Dependencies:

Using npm:

```bash
npm install
Or using yarn:
```
OR
```bash
Copy
yarn install
```

### Configure API Key:

Open src/services/Api.js and replace the API key placeholder with your TMDB API key:

```bash
const API_KEY = "YOUR_TMDB_API_KEY";
```

### Run the Development Server:

```bash
npm run dev
```
OR

```bash
yarn dev
```

Visit http://localhost:3000 (or the port specified by Vite) in your browser.

### Build for Production:

```bash
npm run build
npm run preview
```

### Project Structure

```bash
movie-list/
├── index.html
├── package.json
└── src
    ├── main.jsx
    ├── App.jsx
    ├── components
    │   ├── MovieCard.jsx
    │   └── NavBar.jsx
    ├── contexts
    │   └── MovieContext.jsx
    ├── pages
    │   ├── Home.jsx
    │   └── Favorites.jsx
    ├── services
    │   └── Api.js
    └── css
        ├── index.css
        ├── App.css
        ├── MovieCard.css
        ├── Navbar.css
        ├── Home.css
        └── Favorites.css
```

### Usage
#### Home Page: View popular movies and search by title.
#### Favorites Page: Click the heart icon on a movie card to add or remove it from your favorites.
#### Navigation: Use the NavBar links to switch between pages.

### Contributing
Contributions, issues, and feature requests are welcome! Please open an issue or submit a pull request.

