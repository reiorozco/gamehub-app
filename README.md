<h1 align="center">🎮 GameHub</h1>

<p align="center">
  Discover, search and explore video games — powered by the <a href="https://rawg.io/apidocs">RAWG API</a>.
</p>

<p align="center">
  <a href="https://game-hub-app.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Chakra_UI-319795?style=for-the-badge&logo=chakraui&logoColor=white"/>
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge"/>
</p>

## 🔗 Live Demo

👉 **[game-hub-app.vercel.app](https://game-hub-app.vercel.app)**

## ✨ Features

- 🔍 Search games by title with debounced queries
- 🧩 Filter by genre, platform and sort order
- ♾️ Infinite scroll powered by TanStack Query
- 🌗 Light / dark mode (Chakra UI)
- ⚡ Fast, responsive UI built with Vite

## 🛠️ Tech Stack

- **Core:** React 18 · TypeScript · Vite
- **UI:** Chakra UI · Framer Motion · React Icons
- **Data fetching:** TanStack Query · Axios (RAWG API)
- **State:** Zustand
- **Routing:** React Router

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- A free [RAWG API key](https://rawg.io/apidocs)

### Installation
```bash
git clone https://github.com/reiorozco/gamehub-app.git
cd gamehub-app
npm install
```

### Environment variables
Create a `.env` file based on `.env.example`:
```env
VITE_RAWG_API_KEY=your_rawg_api_key
```

### Run
```bash
npm run dev      # start dev server
npm run build    # production build
npm run preview  # preview production build
```

## 📸 Screenshots

> _Add screenshots or a short GIF here to showcase the UI._

## 📄 License

Released under the [MIT License](LICENSE).
