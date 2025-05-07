# 🏀 NBA Player Similarity & Clustering Analysis

This project aims to compare and group NBA players using **data science techniques**, including **cosine similarity**, **scaling**, **K-Means clustering**, and **interactive visualizations** with Plotly and Seaborn.

---

## 📁 Dataset

The file `nba_stats.csv` contains advanced statistics for 529 NBA players (age, shooting percentages, shot frequency, 2P and 3P shooting, etc.).

---

## 🔧 Technologies & Libraries

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Plotly Express (interactive visuals)
- Google Colab

---

## 🎯 Project Goals

1. **Data Preprocessing**
   - Clean CSV format (replace `;` with `,`, handle NaNs)
   - Normalize numerical features

2. **Similarity Computation**
   - Compute **cosine similarity** between players
   - Build a **similarity matrix**

3. **Clustering**
   - Use **K-Means** algorithm to group similar player profiles

4. **Dimensionality Reduction**
   - Apply **PCA** to reduce feature space to 2D for plotting

5. **Visualization**
   - **Interactive scatter plot** with Plotly
   - **Seaborn heatmap** for visualizing player similarity

---

## 📊 Results

- Players are grouped by playstyle (e.g., 3-point shooters, post players, all-around scorers).
- Similarity between player profiles is clearly visualized.
- The approach is extendable to other sports or domains (e.g., finance, healthcare).

---

## 📁 Notebook Structure

| Section                         | Description |
|----------------------------------|-------------|
| Data loading and cleaning        | CSV reading and delimiter fix |
| Preprocessing & scaling          | Drop unused columns, normalize features |
| Similarity calculation           | Cosine similarity matrix |
| Clustering (K-Means)             | Automatic player grouping |
| Dimensionality reduction (PCA)   | 2D projection |
| Visualization                    | Heatmap and interactive Plotly plot |

---

## 📸 Sample Visualization

### NBA Player Clusters (K-Means + PCA)

![plotly-graph](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/assets/graph.png)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/franckessi237/nba-similarity-analysis.git
