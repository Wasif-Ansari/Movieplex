
# Movieplex

**Movieplex** is a web application that provides a rich movie discovery experience. It allows users to search movies by title, genre, and year, and displays detailed movie information like plot, cast, ratings, and release dates. The app fetches real-time data from The Movie Database API and features an intuitive, responsive user interface designed for both desktop and mobile.

## Features

- **Movie Search:** Search movies by title, genre, or year.
- **Detailed Movie Information:** Includes cast, plot, ratings, release date, and more.
- **Responsive Design:** Mobile-first approach, ensuring a smooth experience across devices.
- **Real-Time Movie Data:** Fetches data from The Movie Database API to display up-to-date information.

## Tech Stack

- **Frontend:**
  - **ReactJS:** For building the user interface.
  - **Vite:** Fast build tool for modern web applications.
  - **SCSS:** For custom styling of the UI.

- **API:**
  - **The Movie Database (TMDb) API:** For fetching real-time movie data such as movie details, images, reviews, and ratings.

## Installation

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Wasif-Ansari/Movieplex.git
    ```

2. Navigate to the project folder:
    ```bash
    cd Movieplex
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and add your TMDb API key:
    ```
    VITE_API_KEY=your_api_key_here
    ```

5. Start the development server:
    ```bash
    npm run dev
    ```

Visit `http://localhost:3000` to use the application locally.

## Usage

- Upon running the app, the user can search for movies by entering keywords in the search bar.
- The app displays a list of matching movies, including their titles, release dates, and posters.
- Clicking on a movie will show detailed information such as plot, cast, ratings, and more.
- The app automatically updates data in real-time using the Movie Database API.

## License

This project is licensed under the MIT License.

---

This **README.md** file provides an in-depth overview of the **Movieplex** project, detailing its features, tech stack, installation steps, and usage instructions. It's designed to be comprehensive for users and contributors alike.
