# 🎬 CineMate - Movie Discovery App

A modern, responsive web application for discovering movies, built with React and Vite. Browse trending films, search for your favorites, and explore detailed information—all in one clean interface.

[**Live Demo**](https://sudoSami.github.io/CineMate/#/) • [Report Bug](https://github.com/sudoSami/CineMate/issues)

## ✨ Features

*   **Trending & Popular Movies**: Discover what's currently popular in cinemas and streaming.
*   **Search Functionality**: Find movies instantly with a live-search interface.
*   **Detailed Movie Views**: Click on any movie to see its overview, rating, release date, and more.
*   **Responsive Design**: Enjoy a seamless experience on desktop, tablet, and mobile devices.
*   **Clean & Modern UI**: A focused, user-friendly interface built with custom CSS.

## 🛠️ Tech Stack

*   **Frontend Framework**: [React](https://reactjs.org/)
*   **Build Tool**: [Vite](https://vitejs.dev/)
*   **Styling**: Vanilla CSS
*   **API**: [The Movie Database (TMDB)](https://www.themoviedb.org/documentation/api)
*   **Deployment**: GitHub Pages

## 🚀 Getting Started

Follow these steps to run the project locally on your machine.

### Prerequisites
*   Node.js (version 16 or later recommended)
*   npm (usually comes with Node.js)

### Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone https://github.com/sudoSami/CineMate.git
    cd CineMate
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Set up your TMDB API Key**
    *   Get a free API key from [TMDB](https://www.themoviedb.org/settings/api).
    *   Create a `.env` file in the project root.
    *   Add your key to the file:
      ```
      VITE_TMDB_API_KEY=your_api_key_here
      ```

4.  **Run the development server**
    ```bash
    npm run dev
    ```
    Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal).

### Building for Production
To create an optimized production build:
```bash
npm run build
