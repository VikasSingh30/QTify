🎧 Qtify – Music Streaming Web App

Qtify is a dynamic and responsive music streaming interface built with React, powered by Vite for fast development and custom styling. The app fetches and displays music albums and songs with real-time filtering, inspired by Spotify-like UI experiences.

---

## VIEW
```bash
https://qtify.vercel.app/
```

---

## 🚀 Features
✅ Fetch and display Top Albums, New Albums, and Songs  
✅ Filter songs by genre (rock, pop, jazz, blues)  
✅ Fully responsive UI using CSS modules  
✅ Modular React components and hooks  
✅ Fast refresh and build time via Vite  

---

## 🏗️ Project Structure

📂 qtify  
├── 📂 public  
│   └── assets/                # Images and icons  
├── 📂 src  
│   ├── components/            # Navbar, Hero, Section, etc.  
│   ├── api/                   # API functions  
│   ├── App.jsx                # Main React component  
│   ├── App.module.css         # Scoped styles  
│   ├── index.css              # Global styles and CSS variables  
│   └── main.jsx               # App entry point  
├── 📄 package.json  
├── 📄 index.html  
└── 📄 vite.config.js  

---

## 🔥 Step-by-Step Guide to Setup the Project

### Step 1: ✅ **Clone the Repository**

```bash
git clone https://github.com/your-username/qtify.git
cd qtify
```
### Step 2: ✅ Install Dependencies

```bash
npm install
```

---

## 📋 Required Packages

| 📦 **Package** | 🧩 **Purpose** | 🛠️ **Command to Install** |
|----------------|---------------|----------------------------|
| ⚛️ **react, react-dom** | Core React library | `npm install react react-dom` |
| ⚡ **vite** | Build tool and dev server | `npm install --save-dev vite` |
| 🧠 **@vitejs/plugin-react** | Vite plugin for JSX and React Fast Refresh | `npm install --save-dev @vitejs/plugin-react` |
| 🧹 **eslint** | Linting and code quality | `npm install --save-dev eslint` |
| 📜 **@eslint/js** | JavaScript ESLint rules | `npm install --save-dev @eslint/js` |
| 🔁 **eslint-plugin-react-hooks** | ESLint rules for React hooks | `npm install --save-dev eslint-plugin-react-hooks` |
| ♻️ **eslint-plugin-react-refresh** | ESLint plugin for React Refresh | `npm install --save-dev eslint-plugin-react-refresh` |
| 🧾 **@types/react, @types/react-dom** | TypeScript types for React | `npm install --save-dev @types/react @types/react-dom` |
| 🌍 **globals** | Predefined global variables for ESLint | `npm install --save-dev globals` |

---

## 📝 Notes
✔️ CSS variables are defined in index.css using :root <br>
✔️ App uses scoped styles via App.module.css and others <br>
✔️ Data fetching logic uses fetchTopAlbums, fetchNewAlbums, and fetchSongs <br>
✔️ Filtering updates songs list dynamically based on selected tab <br>

