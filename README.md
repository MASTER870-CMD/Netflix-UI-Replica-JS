<div align="center">

  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" alt="Netflix Clone Logo" width="200"/>

  <h1>🍿 Netflix Clone - CineStream</h1>

  <p>
    <b>A high-fidelity streaming interface replica powered by the TMDB API.</b>
    <br />
    <i>Features dynamic content fetching, immersive movie trailers, and a seamless responsive UI.</i>
  </p>

  <p>
    <img src="https://img.shields.io/github/license/MASTER870-CMD/Netflix-UI-Replica-JS?style=for-the-badge&color=E50914" alt="License" />
    <img src="https://img.shields.io/badge/API-TMDB-blue?style=for-the-badge&logo=themoviedatabase&logoColor=white" alt="TMDB API" />
    <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status" />
  </p>

  <p align="center">
    <a href="https://master870-cmd.github.io/Netflix-UI-Replica-JS/">View Live Demo</a>
    ·
    <a href="https://github.com/MASTER870-CMD/Netflix-UI-Replica-JS/issues">Report Bug</a>
  </p>
</div>

---

## 📖 Table of Contents
- [📍 Overview](#-overview)
- [✨ Key Features](#-key-features)
- [🛠️ Tech Stack](#-tech-stack)
- [📸 Screenshots](#-screenshots)
- [🚀 Getting Started](#-getting-started)
- [📂 API Configuration](#-api-configuration)
- [🤝 Contributing](#-contributing)

---

## 📍 Overview

This **Netflix Clone** is a front-end masterpiece designed to replicate the immersive experience of the world's leading streaming platform. Unlike static templates, this application is **alive**—it fetches real-time data from **The Movie Database (TMDB)** to display trending movies, top-rated series, and genre-specific content.

It features a custom-built **carousel engine** for browsing and integrates the **YouTube API** to play trailers instantly upon clicking a movie.

> *Keywords: Netflix Clone, TMDB API Project, Movie Streaming App, Frontend Portfolio, UI/UX Design, Vanilla JavaScript.*

---

## ✨ Key Features

* **🔥 Real-Time Content:** Fetches Trending, Top Rated, Action, and Comedy movies dynamically via TMDB API.
* **🎬 Instant Trailers:** Clicks on movies fetch and play related YouTube trailers automatically.
* **📱 Responsive Carousels:** Custom-built horizontal scroll sliders that work perfectly on Mobile and Desktop.
* **🌑 Immersive UI:** Dark-themed, glassmorphism-inspired interface with hero video backgrounds.
* **⚡ Lazy Loading:** Optimized image loading for high performance.
* **🔍 Search Integration:** (Optional) Search functionality to find specific titles.

---

## 🛠️ Tech Stack

Built with a focus on **Asynchronous JS** and **API Handling**.

<div align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/TMDB_API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white" />
</div>

---

## 📸 Screenshots

| **Hero Section** | **Movie Rows** |
|:---:|:---:|
| <img src="https://via.placeholder.com/600x350.png?text=Hero+Banner+UI" alt="Hero Banner" width="100%"> | <img src="https://via.placeholder.com/600x350.png?text=Movie+Carousels" alt="Movie Rows" width="100%"> |

---

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites
* You need a free API Key from [TMDB](https://www.themoviedb.org/).

### Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/MASTER870-CMD/Netflix-UI-Replica-JS.git](https://github.com/MASTER870-CMD/Netflix-UI-Replica-JS.git)
    ```

2.  **Navigate to Folder**
    ```bash
    cd Netflix-UI-Replica-JS
    ```

3.  **Setup API Key**
    * Open `script.js` (or `config.js`).
    * Replace `'YOUR_API_KEY'` with your actual TMDB API Key.

4.  **Launch**
    * Open `index.html` in your browser.

---

## 📂 Project Structure

```text
Netflix-Clone/
├── index.html       # Main structure
├── style.css        # Netflix styling & animations
├── script.js        # API Fetch logic & DOM manipulation
└── README.md        # Documentation
