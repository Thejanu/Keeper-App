# 📝 Keeper App

A small React note-taking demo app built with **Vite** and **Material
UI**.

------------------------------------------------------------------------

## 🌟 Overview

Keeper App is a beginner-friendly project to practice **React state**
and **component composition**.\
It lets you **add** and **delete** notes, similar to Google Keep.

### Main files & components:

-   📂 **Entry**: [`index.html`](index.html),
    [`src/index.jsx`](src/index.jsx)
-   ⚛️ **Main App**: [`App`](src/components/App.jsx)
-   🧩 **Components**:
    -   [`Header`](src/components/Header.jsx)
    -   [`CreateArea`](src/components/CreateArea.jsx)
    -   [`Note`](src/components/Note.jsx)
    -   [`Footer`](src/components/Footer.jsx)
-   🎨 **Styles**: [`public/styles.css`](public/styles.css)

------------------------------------------------------------------------

## ✨ Features

-   ➕ Add notes with **title** and **content**
-   ❌ Delete notes when done
-   🎨 Clean layout with **Material UI** components & icons

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   ⚛️ React 19
-   ⚡ Vite (for dev & build)
-   🎨 Material UI (`@mui/material`, `@mui/icons-material`)
-   📝 CSS ([public/styles.css](public/styles.css))

------------------------------------------------------------------------

## 🚀 Quick Start

1.  Install dependencies

    ``` bash
    npm install
    ```

2.  Start dev server

    ``` bash
    npm run dev
    ```

3.  Build for production

    ``` bash
    npm run build
    ```

4.  Preview build

    ``` bash
    npm run preview
    ```

------------------------------------------------------------------------

## 📸 Screenshot
<img width="1572" height="894" alt="Screenshot 2025-10-01 130546" src="https://github.com/user-attachments/assets/5a359792-2d3d-4cb7-a4ac-2e57921f48a6" />


------------------------------------------------------------------------

## 📂 Project Structure

    keeper-app/
    │── index.html
    │── package.json
    │── vite.config.js
    │── public/
    │   └── styles.css
    └── src/
        ├── index.jsx
        └── components/
            ├── App.jsx
            ├── CreateArea.jsx
            ├── Note.jsx
            ├── Header.jsx
            └── Footer.jsx

------------------------------------------------------------------------

## 📝 Notes & Troubleshooting

-   ✅ Make sure **Node.js** and **npm** are installed
-   🛠️ If Material UI icons don't load → check `package.json` and run
    `npm install`
-   ⚠️ If React errors → check root mount in `src/index.jsx`

------------------------------------------------------------------------

## 🤝 Contributing

This is a simple demo app. You can help by: - Improving accessibility
♿ - Adding persistent storage (like `localStorage`) 💾 - Refactoring
keys in `App` to use unique IDs 🔑

------------------------------------------------------------------------

## 📄 License

MIT License 📜

------------------------------------------------------------------------

💡 *Made with React + Material UI to learn and have fun!* 🚀

