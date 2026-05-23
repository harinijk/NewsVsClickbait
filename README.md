# Clickbait Headline Clustering and Classification

This project explores Natural Language Processing (NLP), unsupervised learning, dimensionality reduction, and classification techniques for analyzing clickbait headlines.

The project uses TF-IDF vectorization, K-Means clustering, PCA visualization, and K-Nearest Neighbors classification to investigate patterns in clickbait and non-clickbait news headlines.

---

## Dataset

Dataset used:
- `clickbait_data.csv`

The dataset contains:
- news headlines
- clickbait labels
- binary clickbait classification

A subset of 20,000 headlines was sampled for experimentation and analysis.

---

## Project Goals

The project investigates:
- whether clickbait headlines naturally form clusters
- how textual features separate clickbait from legitimate news
- how dimensionality reduction can visualize headline patterns
- how classification models perform on headline prediction tasks

---

## Project Sections

### 1. NLP Preprocessing and TF-IDF Feature Extraction

Implemented:
- TF-IDF vectorization
- stemming using NLTK Snowball Stemmer
- stopword removal
- vocabulary filtering

The preprocessing pipeline transformed headlines into numerical feature vectors suitable for machine learning algorithms.

---

### 2. K-Means Clustering

Applied:
- K-Means clustering with 2 clusters
- K-Means clustering with 7 clusters

The clustering analysis explored:
- clickbait percentage within clusters
- cluster purity
- semantic grouping of headlines

---

### 3. Word Cloud and Cluster Interpretation

Generated:
- word clouds for each cluster
- representative headlines closest to cluster centers

This section analyzed:
- dominant words
- thematic cluster structure
- semantic similarities between headlines

---

### 4. Cluster Error Analysis

The project identified:
- legitimate news headlines appearing in clickbait clusters
- clickbait headlines appearing in news clusters

Additional manually created headlines were tested against learned clusters to evaluate clustering behavior and semantic separation.

---

### 5. PCA Visualization

Used Principal Component Analysis (PCA) to:
- reduce TF-IDF feature dimensionality
- visualize headline distributions in 3D
- analyze explained variance

Interactive 3D visualizations were created using Plotly.

---

### KNN Classification

Implemented:
- K-Nearest Neighbors classifier
- PCA dimensionality reduction before classification

Evaluation metrics:
- training accuracy
- testing accuracy
- F1 score

The classifier predicted whether headlines were clickbait or legitimate news.

---

## Technologies Used

- Python
- scikit-learn
- pandas
- NumPy
- matplotlib
- seaborn
- Plotly
- NLTK
- WordCloud

---

## NLP and Machine Learning Concepts Used

- TF-IDF Vectorization
- Text Stemming
- Stopword Removal
- K-Means Clustering
- PCA
- Dimensionality Reduction
- K-Nearest Neighbors
- Cosine Distance Analysis
- Cluster Analysis
- Feature Extraction

---

## Results

The experiments demonstrated that:
- clickbait headlines form identifiable semantic clusters
- TF-IDF features effectively capture clickbait language patterns
- PCA projections reveal meaningful structure in headline data
- some headlines naturally overlap between clickbait and legitimate news categories
- KNN classification achieved strong predictive performance after dimensionality reduction

The project highlights how unsupervised learning and NLP techniques can analyze online media and headline behavior.
