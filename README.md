# 🎬 Movie Finder

Movie Finder is a React-based web application that allows users to search for movies, browse details, and save their favorite movies for quick access. The application fetches movie data from an external movie database API and provides a clean, responsive user interface for an enhanced movie discovery experience.

## 🚀 Features

* 🔍 Search movies by title
* 🎥 View movie posters, ratings, and details
* ❤️ Add and remove movies from Favorites
* 📱 Responsive design for desktop and mobile devices
* ⚡ Fast performance using React and Vite
* 🌐 API integration for real-time movie data

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Context API
* CSS3

### API

* Movie Database API (TMDB/OMDB)

### Deployment

* Vercel

---

## 📂 Project Structure

```text
src/
│
├── components/
│   ├── MovieCard.jsx
│   └── NavBar.jsx
│
├── contexts/
│   └── MovieContext.jsx
│
├── css/
│   ├── App.css
│   ├── Favorites.css
│   ├── Home.css
│   ├── Index.css
│   ├── MovieCard.css
│   └── NavBar.css
│
├── Pages/
│   ├── Favorites.jsx
│   └── Home.jsx
│
├── services/
│   ├── api.js
│   └── config.js
│
├── App.jsx
└── main.jsx
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/rajasatyam/Movie-Finder.git
cd Movie-Finder/Frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_API_KEY=YOUR_API_KEY
```

Replace `YOUR_API_KEY` with your Movie Database API key.

### 4. Start Development Server

```bash
npm run dev
```

The application will run at:

```text
http://localhost:5173
```

---

## 🏗️ Build for Production

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

## 🧠 Learning Outcomes

Through this project, I gained hands-on experience with:

* React Component Architecture
* State Management using Context API
* API Integration
* Responsive UI Design
* React Router Navigation
* Vite Build Tool
* Deployment with Vercel

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---
.
