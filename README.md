# MovieLand

A modern React application for searching and displaying movie information using the OMDB API.

**Created by: Phạm Lê Ngọc Sơn**

## Project Overview

MovieLand is a responsive web application that allows users to search for movies and view relevant information such as poster images, release years, and movie types. The application fetches data from the OMDB API and presents it in an aesthetically pleasing card-based layout.

## Project Structure

```
movie_land_react/
│
├── public/                  # Public assets and HTML
│   ├── index.html           # Entry HTML file
│   ├── favicon.ico          # Website favicon
│   ├── logo192.png          # Small app logo
│   ├── logo512.png          # Large app logo
│   ├── manifest.json        # PWA manifest file
│   └── robots.txt           # Robots crawling rules
│
├── src/                     # Source code
│   ├── App.js               # Main application component
│   ├── App.css              # Application styling
│   ├── MovieCard.jsx        # Movie card component
│   ├── index.js             # JavaScript entry point
│   └── search.svg           # Search icon SVG
│
├── package.json             # Project dependencies and scripts
├── package-lock.json        # Locked dependencies
└── README.md                # Project documentation
```

## Technology Stack

- **React**: Frontend library for building user interfaces
- **JavaScript (ES6+)**: Programming language
- **CSS3**: Styling language with modern features
- **OMDB API**: External API for fetching movie data

## Features

- **Movie Search**: Search for movies by title
- **Responsive Design**: Works on various screen sizes
- **Dynamic Content Loading**: Fetches movie data in real-time
- **Error Handling**: Shows appropriate messages when no movies are found
- **Visual Feedback**: Displays movie posters and information in an organized layout

## API Integration

The application integrates with the OMDB API to fetch movie data. The API key is included in the application code for demonstration purposes, but in a production environment, it should be stored securely.

## How to Use

1. **Installation**:
   ```bash
   # Clone the repository
   git clone <repository-url>
   
   # Navigate to the project directory
   cd movie_land_react
   
   # Install dependencies
   npm install
   ```

2. **Running the Application**:
   ```bash
   # Start the development server
   npm start
   ```

3. **Using the Application**:
   - Once the application is running, open your browser and navigate to `http://localhost:3000`
   - Enter a movie title in the search box
   - Click the search icon or press Enter
   - Browse through the movie results displayed as cards

## Component Details

### App Component (App.js)
- Main application component
- Manages state for movie search and results
- Handles API requests and response processing
- Renders the search interface and movie results

### MovieCard Component (MovieCard.jsx)
- Displays individual movie information
- Renders movie poster, title, year, and type
- Handles cases where poster images are not available

## Customization

You can customize the application by:
- Modifying the CSS in App.css to change the visual appearance
- Adding additional features like movie details or user authentication
- Implementing sorting or filtering options for movie results

## Building for Production

To build the application for production:
```bash
npm run build
```

This creates an optimized production build in the `build` folder that can be deployed to any static hosting service.

## License

This project is open source and available for educational and personal use.

---

**Created by Phạm Lê Ngọc Sơn**
