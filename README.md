# 🎬 Movie Recommender System using Streamlit

Welcome to the **Movie Recommender System** – a web application that helps users find movie suggestions based on their preferences for **Genre**, **Language**, and **Theme**. Built using **Streamlit** and a basic **Machine Learning model (KNN)**, this project demonstrates a clean UI, simple logic, and customizable design.

---

## 🌐 Demo

![image](https://github.com/user-attachments/assets/c01d3fdc-68ef-4eea-b680-e3f9e7397890)


## 🧠 How It Works

This app allows users to:

1. Select a **Genre** (e.g., Action, Comedy, Drama).
2. Choose a **Language** (e.g., English, Hindi, Bengali).
3. Pick a **Theme** (e.g., Love, Friendship, Patriotism).

💡 Once the preferences are selected, the system searches for exact matches in a movie dataset. If an exact match is found, it shows the top results. If not, it falls back to a similarity-based search using **K-Nearest Neighbors (KNN)** with **OneHotEncoding** of categorical features.

---

## 📸 Features

- 🎭 Filter movies based on Genre, Language, and Theme
- 🎯 Instant recommendations via button click
- 🖼️ Custom background and stylized UI using CSS
- 🤖 Fallback logic using machine learning (KNN) when exact match is not available
- 🔁 Easily extendable dataset and logic

---

## 🧾 Dataset

Located at: `data/movies.csv`

**Columns:**
- `Movie Name`
- `Genre`
- `Language`
- `Theme`

Example row:
```csv
Movie Name,Genre,Language,Theme
3 Idiots,Comedy,Hindi,Friendship


