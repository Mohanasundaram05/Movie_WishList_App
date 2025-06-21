# 🎬 Movie WishList App

A modern React application for managing your personal movie collection, tracking watched films, and organizing your favorites. Built with React 19, Vite, and React Router.

## ✨ Features

- **Movie Management**: Add, edit, and delete movies from your collection
- **Watch Status Tracking**: Mark movies as watched or unwatched
- **Favorites System**: Create and manage your favorite movies list
- **Statistics Dashboard**: View insights about your movie collection
- **Responsive Design**: Modern UI that works on desktop and mobile
- **Local Storage**: Your movie data persists between sessions

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Movie_WishList_App
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

## 📁 Project Structure

```
Movie_WishList_App/
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable UI components
│   │   ├── Footer.jsx
│   │   ├── MovieCard.jsx
│   │   ├── MovieList.jsx
│   │   ├── MovieStats.jsx
│   │   └── NavBar.jsx
│   ├── context/           # React Context for state management
│   │   └── MovieContext.jsx
│   ├── data/              # Initial data and constants
│   │   └── initialMovies.js
│   ├── layouts/           # Layout components
│   │   └── MainLayout.jsx
│   ├── pages/             # Page components
│   │   ├── Favorites.jsx
│   │   ├── Home.jsx
│   │   └── MovieForm.jsx
│   ├── routers/           # Routing configuration
│   │   └── AppRouter.jsx
│   ├── App.jsx            # Main application component
│   └── main.jsx           # Application entry point
├── package.json
└── vite.config.js
```

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 🎯 Usage

### Adding Movies
1. Navigate to the Home page
2. Use the "Add Movie" form to enter movie details:
   - Title
   - Year
   - Genre
3. Click "Add Movie" to save

### Managing Your Collection
- **Mark as Watched**: Toggle the watch status of any movie
- **Add to Favorites**: Click the heart icon to add/remove from favorites
- **Delete Movie**: Remove movies you no longer want to track

### Viewing Statistics
- Visit the Stats page to see:
  - Total number of movies
  - Watched vs unwatched count
  - Favorite movies count
  - Genre distribution

### Favorites Page
- View all your favorite movies in one place
- Manage your favorites list

## 🛠️ Technologies Used

- **React 19** - Modern React with latest features
- **Vite** - Fast build tool and development server
- **React Router DOM** - Client-side routing
- **UUID** - Unique ID generation
- **ESLint** - Code linting and quality

## 🎨 Features in Detail

### State Management
The app uses React Context API for global state management, providing:
- Movie collection data
- Favorites management
- CRUD operations for movies

### Routing
- `/` - Home page with movie list and add form
- `/favorites` - Favorites page
- `/stats` - Statistics dashboard

### Data Persistence
Movie data is stored in local state and persists during the session. The app comes with sample data including popular movies like:
- Inception (2010)
- The Godfather (1972)
- Interstellar (2014)
- The Dark Knight (2008)
- And more...

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License
This project is licensed under the MIT License – see the [MIT](LICENSE) file for details.
