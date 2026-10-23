# Photo Collections

A photo gallery application built with React. Users can browse photo collections, filter them by category, search by name, and navigate between pages.

## Features

- Display photo collections with image previews.
- Filter collections by category (Sea, Mountains, Architecture, Cities).
- Search collections by name.
- Navigate between pages using pagination.
- Fetch collection data from an external API.
- Display a loading message while fetching data.
- Handle errors during API requests.

## Technologies

- React
- JavaScript (ES6+)
- HTML
- SCSS
- Fetch API
- MockAPI

## How It Works

The application uses React hooks to manage its state:

- **useState** — stores photo collections, selected category, current page, search input, and loading status.
- **useEffect** — fetches data from the API when the selected category or page changes.

Photo collections are retrieved from MockAPI and displayed using reusable React components.

Users can select a category, search for collections by name, and switch between pages.

## Getting Started

To run the project locally:

### 1. Clone the repository

Clone the project from GitHub and open its folder.

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

### 4. Open the application

Open `http://localhost:3000` in your browser.

## Project Structure

```text
src/
├── App.jsx
├── Collection.jsx
├── index.scss
└── index.js
```

- **App.jsx** — main application component, including filtering, searching, pagination, and API requests.
- **Collection.jsx** — reusable component for displaying a photo collection.
- **index.scss** — application styles.
- **index.js** — application entry point.

## Purpose

This project was created as a beginner React practice project to improve skills in:

- Working with React components and props.
- Managing state with useState.
- Using useEffect for API requests.
- Fetching and displaying external data.
- Rendering lists with map().
- Filtering arrays with filter().
- Implementing category filters, search, and pagination.
- Handling asynchronous operations and loading states.

## Credits

This project was created for educational purposes while following a React tutorial.
