# 🎬 Movie Recommender System

An intelligent and visually appealing movie recommender web app that suggests movies similar to your favorites using content-based filtering. Built using Streamlit, this project leverages a preprocessed movie dataset and a similarity matrix to give instant, accurate recommendations with poster previews.

---

## 🔍 Description

The Movie Recommender System allows users to select a movie from a dropdown and receive five similar movie suggestions. It fetches movie posters in real-time using the TMDb API, enhancing the user experience with a clean and interactive interface. Whether you're a movie buff or just looking for something new to watch, this app will help you discover great titles based on your preferences.

---

## 🛠️ Tech Stack

- **Python** – Core logic and data handling
- **Streamlit** – Web application framework
- **Pandas & Pickle** – Data preprocessing and loading
- **scikit-learn** – Similarity computation
- **TMDb API** – Fetching real-time movie posters
- **gdown** – To fetch large preprocessed files (like similarity matrix) from Google Drive

---

## ✨ Features

- 🎞️ Recommend 5 similar movies based on the selected title
- 🖼️ Fetch and display movie posters dynamically
- ⚡ Fast performance using cached data and precomputed similarity matrix
- 🎨 Clean and responsive user interface with interactive elements
- ☁️ Deployed and accessible through Streamlit Cloud

---

## 🧠 How Recommendations Are Generated

The app uses **Content-Based Filtering**:
1. A feature vector is created for each movie using text-based metadata (like genres, cast, etc.).
2. A similarity matrix is generated using cosine similarity between these vectors.
3. When a user selects a movie, the app looks up its index and finds the most similar movies based on the precomputed matrix.
4. Posters for the recommended movies are fetched from TMDb via their API.

---

## 🚀 Live App

👉 [Click here to try the live app](https://<your-streamlit-app-url>)  
*(Replace the URL with your actual Streamlit deployment link)*

---

## 📦 Source Code

👉 [View the source code here](https://github.com/<your-username>/movie-recommender-system)  
*(Replace the URL with your code repository link)*

---

## 🖼️ Demo Preview

![Demo Screenshot](images/screenshot1.png)

---

## 📧 Contact

If you have any questions or feedback, feel free to reach out!

