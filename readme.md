````
# Webpack + Babel Starter Template

This is a lightweight starter project using **Webpack** and **Babel** — no frameworks, no clutter. It helps you write modern JavaScript (ES6+) and bundle it for the browser.

---

## 🔧 Features

- ✅ ES6+ support via Babel
- ✅ Bundling with Webpack
- ✅ Live development server (via `webpack-dev-server`)
- ✅ Clean HTML template injection (via `html-webpack-plugin`)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/webpack-babel-starter.git
cd webpack-babel-starter
````

> Replace the GitHub link with your actual repository URL.

---

### 2. Install dependencies

Make sure you have **Node.js** installed. Then run:

```bash
npm install
```

---

### 3. Run the development server

```bash
npm start
```

This will start the dev server and open your browser to [http://localhost:3000](http://localhost:3000)

---

### 4. Build for production

```bash
npm run build
```

The output will be in the `dist/` folder, ready to be deployed.

---

## 📁 Project Structure

```
webpack-babel-app/
├── dist/              # Output folder & HTML template
│   └── index.html
├── src/               # Your modern JavaScript goes here
│   └── index.js
├── .babelrc           # Babel configuration
├── package.json       # Project metadata & scripts
├── webpack.config.js  # Webpack configuration
└── .gitignore
```



