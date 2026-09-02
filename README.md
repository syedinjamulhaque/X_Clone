# X Clone

A responsive, dark-mode recreation of the **X (formerly Twitter) home timeline**, built as a front-end UI project using Vite and Tailwind CSS.

The project recreates the desktop and mobile experience with a left navigation rail, central timeline, and a desktop-only discovery sidebar.

> **Note:** This is a front-end UI project. It does not include authentication, database integration, real-time posts, search functionality, or other backend features.

## 🚀 Live Demo

**[View Live Demo](YOUR_NETLIFY_URL_HERE)**

## ✨ Features

- 📱 Fully responsive layout for desktop, tablet, and mobile
- 🌙 X-inspired dark theme
- 🧭 Sticky left navigation
- 📰 Central home timeline with sample posts
- ✍️ Post composer interface
- 🖼️ Image-rich sample posts
- ⚡ Lazy-loaded local artwork for improved loading performance
- 🔍 Sticky search area on desktop
- 📑 Sticky timeline tabs
- ⭐ Premium section
- 📰 News and trending sections
- 👥 "Who to follow" section
- 🎨 X-inspired icons, spacing, colors, and interaction states
- 📐 Responsive three-column layout that adapts to smaller screens

## 🛠️ Built With

- [Vite](https://vite.dev/)
- [Tailwind CSS](https://tailwindcss.com/) v4
- HTML5
- JavaScript
- [Material Symbols](https://fonts.google.com/icons)

## 📦 Getting Started

### Prerequisites

Make sure you have a current **Node.js LTS** release installed.

npm comes bundled with Node.js.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/syedinjamulhaque/X_Clone.git
cd X_Clone
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open the local URL shown by Vite in your browser.

Typically:

```text
http://localhost:5173
```

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the Vite development server |
| `npm run build` | Creates an optimized production build in `dist/` |
| `npm run preview` | Serves the production build locally |

## 📁 Project Structure

```text
X_Clone/
├── assets/             # Artwork used by sample timeline posts
├── public/             # Public assets, including the X icon
├── src/
│   ├── main.js         # Application entry point
│   └── style.css       # Tailwind CSS import
├── index.html          # Main page markup and UI layout
├── package.json        # Project scripts and dependencies
└── vite.config.js      # Vite and Tailwind configuration
```

## 🎨 Customization

You can easily customize the project by:

- Updating sample posts and sidebar content in `index.html`
- Adding or replacing feed artwork inside `assets/`
- Updating image paths in `index.html`
- Adjusting colors, spacing, sizing, and responsive behavior using Tailwind utility classes

## ⚡ Performance

The feed uses **lazy loading for local images** so that images are loaded as they become necessary instead of loading every image immediately.

This helps reduce the initial page load, especially on image-heavy feeds.

## ⚠️ Notes

- Material Symbols are loaded from Google Fonts, so an internet connection is required for the icons to appear.
- This project is intended for educational and portfolio purposes.
- X branding and design elements are used only to recreate the interface for learning purposes.
- Make sure you have the necessary rights to use and redistribute any images added to the project.

### 👨‍💻 Author

**Syed Injamul Haque**
