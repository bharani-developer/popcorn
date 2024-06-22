# 🍿 Popcorn - Movie Watchlist App

![Popcorn](https://github.com/bharani-developer/popcorn/blob/main/public/popcorn.png)
![Popcorn](https://github.com/bharani-developer/popcorn/blob/main/public/popcorn1.png)

Popcorn is a React application that allows users to search for movies from the IMDb database, add or remove movies from their watchlist, calculate the total time to watch the movies, and give ratings to the movies.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Components](#components)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Search movies from the IMDb database
- Add or remove movies from a personal watchlist
- Calculate the total time required to watch all movies in the watchlist
- Rate movies and see average ratings

## Demo

Check out the live demo [here](https://your-demo-link.com).

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/bharani-developer/popcorn.git
    cd popcorn
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Start the development server:**

    ```bash
    npm start
    ```

    The app will be available at `http://localhost:3000`.

## Usage

1. **Search for a movie:**
    - Use the search bar to find movies from the IMDb database.

2. **Add a movie to the watchlist:**
    - Click the "Add to Watchlist" button next to the movie you want to add.

3. **Remove a movie from the watchlist:**
    - Click the "Remove from Watchlist" button next to the movie you want to remove.

4. **Rate a movie:**
    - Select a star rating for the movie. The average rating will be updated accordingly.

5. **View total watch time:**
    - The total time required to watch all movies in the watchlist is displayed.

## Code Structure

- **`src/App.js`:** Main component that manages the state and renders the main layout.
- **`src/components/Search.js`:** Component to search for movies.
- **`src/components/MovieList.js`:** Component to display the list of movies.
- **`src/components/Movie.js`:** Component to display a single movie.
- **`src/components/Watchlist.js`:** Component to display the user's watchlist.
- **`src/components/TotalTime.js`:** Component to display the total watch time.
- **`src/components/Rating.js`:** Component to handle movie ratings.

## Components

### `App.js`

This is the main component where the state is managed. It includes functions to add movies to the watchlist, remove them, and calculate the total watch time.

### `Search.js`

This component includes a search bar and handles the search functionality.

### `MovieList.js`

This component takes a list of movies as a prop and renders them. It also handles sorting and filtering.

### `Movie.js`

This component represents a single movie in the list. It includes buttons to add or remove the movie from the watchlist and a rating feature.

### `Watchlist.js`

This component displays the user's watchlist, showing all movies that have been added.

### `TotalTime.js`

This component calculates and displays the total time required to watch all movies in the watchlist.

### `Rating.js`

This component allows users to rate movies and displays the average rating for each movie.

## Technologies Used

- **Frontend**: React, React Router, CSS
- **API**: IMDb API *(or another movie database API)*
- **State Management**: React Context API or Redux

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [Bharani karthikeyan](mailto:bharani.developer@gmail.com@example.com)

Project Link: [https://github.com/bharani-developer/popcorn](https://github.com/bharani-developer/popcorn)
