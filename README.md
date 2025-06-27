# 🛠️ Webpack Starter Template

A modern Webpack 5 boilerplate for vanilla JavaScript projects. Includes HTML/CSS/JS bundling, image support, dev server with hot reload, and GitHub Pages deployment.

---

## 📁 Folder Structure

```
webpack-template/
├── dist/              # Final build output
│   └── index.html
├── src/               # Source files
│   ├── index.js
│   ├── index.css
│   └── index.html
├── .gitignore
├── package.json
├── webpack.config.js
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the template

```bash
git clone https://github.com/your-username/webpack-template.git
cd webpack-template
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

> Opens automatically at `http://localhost:8080/` with hot module replacement.

### 4. Build for production

```bash
npm run build
```

> Bundled output will be in the `dist/` folder.

### 5. Clean the build folder

```bash
npm run clean
```

### 6. Deploy to GitHub Pages

```bash
npm run deploy
```

> Pushes the `dist/` folder to the `gh-pages` branch using `git subtree`.

---

## ⚙️ Features

- ✅ Webpack 5
- ✅ Live reload with `webpack-dev-server`
- ✅ HMR (Hot Module Replacement) for fast development
- ✅ Image asset handling (PNG, JPG, SVG, etc.)
- ✅ HTML template support via `html-webpack-plugin`
- ✅ CSS bundling via `style-loader` and `css-loader`
- ✅ Clean build system
- ✅ One-command deploy to GitHub Pages

---

## 📜 Scripts

| Command          | Description                         |
| ---------------- | ----------------------------------- |
| `npm run dev`    | Start dev server with hot reload    |
| `npm run build`  | Build production-ready code         |
| `npm run clean`  | Delete `dist/` folder               |
| `npm run deploy` | Deploy `dist/` to GitHub Pages      |
| `npm run lint`   | Run ESLint (if configured)          |
| `npm run test`   | Run tests with Jest (if configured) |

---

## 📦 Dependencies

| Package               | Purpose                |
| --------------------- | ---------------------- |
| `webpack`             | Core bundler           |
| `webpack-cli`         | Command-line interface |
| `webpack-dev-server`  | Local dev server + HMR |
| `html-webpack-plugin` | Auto-generates HTML    |
| `style-loader`        | Injects CSS into DOM   |
| `css-loader`          | Resolves CSS imports   |
| `html-loader`         | Enables HTML imports   |

---

## 📄 License

MIT — Free to use in personal and commercial projects.

---

## 🙌 Acknowledgments

Inspired by the [**Full Stack JavaScript Course**](https://www.theodinproject.com/paths/full-stack-javascript) from [**The Odin Project**](https://www.theodinproject.com/), a free and open-source curriculum for learning web development.
