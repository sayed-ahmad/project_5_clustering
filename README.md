# 🎧 Case Study: Moosic – Playlist Creation

## 📌 Overview

Moosic is a startup that curates personalized playlists created by music experts, capturing different moods and styles. As the company scales, manual playlist creation is becoming a bottleneck.

This project explores how **Data Science can help automate playlist generation** using Spotify audio features and clustering techniques.

---

## 🎯 Project Objective

To develop an initial **data-driven playlist generation prototype** by:

* Using Spotify audio features (e.g., tempo, energy, danceability)
* Applying clustering algorithms (K-Means)
* Grouping similar songs into automatically generated playlists

---

## 🧠 Business Problem

Moosic faces a scaling challenge:

* Music experts cannot create playlists fast enough to match user demand
* The company wants to explore whether **machine learning can replicate or enhance human curation**
* There is skepticism about whether audio features can truly represent “mood” or “style”

This project aims to evaluate whether data-driven methods can support or enhance human judgment.

---

## 🔬 Methodology

### 1. Data Source

* Dataset collected via **Spotify API**
* Contains audio features such as:

  * Tempo
  * Energy
  * Danceability
  * Valence
  * Acousticness

---

### 2. Data Processing

* Cleaned and prepared audio feature dataset
* Standardized numerical variables for clustering
* Selected relevant features for similarity analysis

---

### 3. Machine Learning Approach

* Applied **K-Means clustering** to group similar songs
* Generated clusters interpreted as potential playlists
* Analyzed cluster structure and cohesion

---

## 📊 Key Questions Explored

* Can Spotify audio features capture human-perceived similarity between songs?
* Do clusters reflect meaningful musical groupings (e.g., rock, classical, electronic)?
* Is K-Means a suitable method for playlist generation?
* Should alternative clustering or recommendation methods be explored?

---

## 🛠️ Skills & Tools

* Python
* Pandas & NumPy
* Scikit-learn (K-Means clustering)
* Data preprocessing & feature scaling
* Unsupervised machine learning
* Exploratory data analysis

---

## 📈 Outcome

* Built an initial **automated playlist generation prototype**
* Demonstrated how clustering can group songs based on audio similarity
* Provided insights into the strengths and limitations of using audio features for music classification
* Initiated discussion on improving playlist generation with more advanced models

---

## 📂 Repository Structure

| File / Folder | Description                              |
| ------------- | ---------------------------------------- |
| `/data`       | Spotify audio feature dataset            |
| `/notebooks`  | Data analysis and clustering experiments |
| `/models`     | K-Means clustering implementation        |
| `/visuals`    | Cluster visualizations                   |
| `/Presentation`| final presentation                      |
| `README.md`   | Project documentation                    |

---

## 🤝 Contributor

* *(Sami)*

---

## 🚀 Key Takeaway

This project demonstrates how **unsupervised learning (K-Means clustering)** can be used to transform raw audio features into structured, meaningful playlist groups, bridging the gap between data science and music curation.

---


