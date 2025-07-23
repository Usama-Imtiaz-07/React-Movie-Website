# Movie Database App

## Overview
Movie Database App is a dynamic, single-page web application built with **React.js**, showcasing my skills in modern frontend development. Integrated with the **TMDB API**, this project enables users to explore trending movies, manage a favorites list, and navigate a responsive UI with seamless page routing. Styled with **Tailwind CSS** and enhanced with features like a trending movie carousel and an in-development trailer playback system, this app demonstrates my ability to build engaging, API-driven applications suitable for a full stack portfolio.

## 🌟 Live Demo
Experience the app in action: [View Live Demo on Vercel](https://react-movie-app-rho-peach.vercel.app/)  
*Note*: The demo is hosted on Vercel, which automatically generates a deployment link. For the best experience, explore the trending carousel, add movies to favorites, and navigate between pages.

## Key Features
- **Movie Browsing**: Fetches and displays movie data (titles, posters, descriptions) from the TMDB API.
- **Trending Carousel**: Interactive carousel showcasing trending movies for an engaging user experience.
- **Favorites Management**: Add or remove movies from a favorites list, persisted in local storage.
- **Page Routing**: Seamless navigation using **React Router** for home, movie details, and favorites pages.
- **Responsive Design**: Crafted with **Tailwind CSS** for optimal performance across desktops, tablets, and mobiles.
- **Trailer Playback (In Development)**: Routes to a dedicated page to play movie trailers upon clicking a movie card.
- **State Management**: Leverages **React Context API**, `useState`, and `useEffect` for efficient data handling and API integration.

## Technical Highlights
This project demonstrates my proficiency in:
- **Frontend Development**: Building reusable React components with hooks (`useState`, `useEffect`) and Context API for state management.
- **API Integration**: Fetching and processing data from the TMDB API with robust error handling.
- **Responsive UI/UX**: Designing a polished, mobile-first interface using Tailwind CSS.
- **Routing**: Implementing client-side navigation with React Router for a smooth single-page app experience.
- **Data Persistence**: Utilizing local storage to maintain user favorites across sessions.
- **Modern JavaScript**: Writing clean, ES6+ code for maintainability and scalability.

## Technologies Used
- **React.js**: Core library for building dynamic, component-based UI.
- **React Router**: Enables seamless page navigation.
- **Tailwind CSS**: Utility-first framework for rapid, responsive styling.
- **TMDB API**: Provides real-time movie data.
- **JavaScript (ES6+)**: Drives application logic and interactivity.
- **HTML5**: Structures the application.
- **Vercel**: Hosts the deployed application for live access.

## Installation
To run the Movie Database App locally:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/movie-database-app.git
   cd movie-database-app
   ```
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Set Up TMDB API Key**:
   - Obtain an API key from [TMDB](https://www.themoviedb.org/).
   - Create a `.env` file in the project root:
     ```
     REACT_APP_TMDB_API_KEY=your-api-key
     ```
4. **Run the Application**:
   Start the development server:
   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## Usage
- **Explore Movies**: Browse movies on the homepage, fetched from the TMDB API.
- **Trending Carousel**: Interact with the carousel to view trending movies.
- **Manage Favorites**: Click the heart/star icon to add/remove movies from your favorites list.
- **Navigate Pages**: Use the navigation bar to access home, movie details, or favorites pages.
- **Trailer Playback (In Development)**: Click a movie card to view its trailer on a separate page.
- **Persistent Data**: Favorites are saved in local storage for continuity.

## Project Structure
```plaintext
movie-database-app/
├── public/
│   ├── index.html       # Main HTML file
│   └── ...              # Static assets (e.g., favicon)
├── src/
│   ├── components/      # Reusable components (e.g., MovieCard, Carousel)
│   ├── pages/           # Page components (e.g., Home, MovieDetails, Favorites)
│   ├── context/         # Context API for global state
│   ├── styles.css       # Tailwind CSS and custom styles
│   ├── App.js           # Main app with routing logic
│   └── index.js         # React entry point
├── .env                 # Environment variables (TMDB API key)
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
```

## Why This Project?
This app showcases my ability to:
- Build a **production-ready frontend** with React, integrating real-world APIs.
- Create a **responsive, user-friendly UI** with Tailwind CSS.
- Implement **scalable state management** using Context API and hooks.
- Deliver a **polished portfolio piece** suitable for full stack roles.

## Contributing
I welcome feedback and contributions! To contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request with a detailed description.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
I’m excited to connect with recruiters and discuss how my skills can contribute to your team!    
- **Email**: [your-email@example.com](mailto:osamaimtiaz677@gmail.com)  
- **LinkedIn**: [your-linkedin-profile](https://www.linkedin.com/in/usama-imtiaz-a2a66721a/)  
Feel free to explore the [live demo](https://react-movie-app-rho-peach.vercel.app/) and reach out for collaboration opportunities.

## Acknowledgments
- [TMDB](https://www.themoviedb.org/) for the movie data API.
- [Tailwind CSS](https://tailwindcss.com/) for streamlined styling.
- [React Router](https://reactrouter.com/) for navigation.
- [Vercel](https://vercel.com/) for hassle-free deployment.
