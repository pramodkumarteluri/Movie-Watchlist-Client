# 🎬 Movie-Watchlist - Frontend (React)

This is the **frontend** of the Movie-Watchlist application built using **React.js** and styled with **Bootstrap**. It connects to a backend server via REST API to manage a user's list of movies.

---

## ⚙️ Tech Stack

- React 19
- React Router DOM 7
- Axios for API calls
- Bootstrap 5 for styling
- React Toastify for notifications

---

## 📁 Folder Structure

```
client/
├── public/
│   └── index.html
├── src/
│   ├── components/      # components (AddMovie.js, EditMovie.js, MovieCard.js, MovieList.js, Navbar.js)
│   ├── pages/          # pages (Home.js, Register.js, Login.js, Dashboard.js)
|   |── utils/           # utils (api.js)
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   ├── .env
│   └── README.md
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

```

---

## 🔧 Setup & Installation

1. Navigate to the `client/` folder:
   ```bash
   cd client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

---

## 🔁 Proxy Configuration

To connect to the backend server, the following proxy is set in `package.json`:

```json
"proxy": "https://movie-watchlist-server-y5il.onrender.com/"
```

---

## 🚀 Features

- User registration and login
- Add, edit, delete, and mark movies as watched
- Protected routes based on login status
- Interactive alerts and popups

---

## 🧑‍💻 Author

Developed by **Pramod Kumar**  
[LinkedIn](https://www.linkedin.com/in/pramodkumarteluri/) | [GitHub](https://github.com/pramodkumarteluri)
