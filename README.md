# 🎬 React Movie Database

A React application to search for movies and save your favourites using [The Movie Database (TMDb)](https://www.themoviedb.org/) API.

---

## 🚀 Features

* 🔍 **Search Movies** by title.
* ⭐ **Add/Remove Favourites** to track movies you like.
* 📄 **View Movie Details** including poster, release date, and overview.
* 💾 **Persistent Favourites** using Local Storage.
* 🎨 **Responsive UI** built with React and CSS/Tailwind.

---

## 🛠️ Tech Stack

* [React](https://react.dev/)
* [TMDb API](https://developer.themoviedb.org/reference/intro/getting-started)
* CSS
* JavaScript (ES6+)

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Kek-Lord/React-Movies-Database.git
cd React-Movies-Database/frontend
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**
   Create a `.env` file in the root of `frontend`:

```env
VITE_API_KEY=your_api_key_here
```

4. **Run the development server**

```bash
npm run dev
```

5. **Build for production**

```bash
npm run build
```

---

## ⚙️ Usage

* Search movies by entering a title in the search bar.
* Click ⭐ to add or remove a movie from favourites.
* View your saved favourites in the dedicated section.

---

## 📂 Project Structure

```
src/
├── components/      # Reusable UI components
├── pages/           # Home, Favourites pages
├── services/        # TMDb API service
├── App.jsx          # Root component
└── main.jsx         # Entry point
```

---

## 🔑 API Key

You need a free API key from TMDb:

1. Sign up at [TMDb](https://www.themoviedb.org/signup).
2. Navigate to **Settings > API** and request an API key.
3. Add it to `.env` as `VITE_API_KEY`.

---

## 🤝 Contributing

* Fork the repo
* Create a feature branch
* Submit a pull request

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

* [The Movie Database (TMDb)](https://www.themoviedb.org/) for providing the API.
* React community for amazing tools and support.
