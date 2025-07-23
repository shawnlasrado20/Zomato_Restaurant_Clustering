# Zomato_Restaurant_Clustering

# Restaurant Clustering Analysis on Zomato Reviews Dataset

This project analyzes a Zomato restaurant reviews dataset combined with metadata such as reviewer counts, follower counts, pictures, ratings, and sentiment scores derived from customer reviews. The goal is to segment restaurants based on multiple attributes to uncover meaningful clusters that help businesses better understand customer preferences and optimize their offerings.

---

## Project Overview

The dataset contains detailed information on restaurants along with user reviews collected from Zomato. Features include:
- Restaurant names and cuisine types
- Ratings and number of pictures
- Reviewer and follower counts extracted from metadata
- Sentiment scores generated from textual reviews
- Operating timings categorized into morning, evening, and all-day

Using this rich dataset, unsupervised machine learning clustering techniques such as KMeans, Agglomerative Hierarchical Clustering, and DBSCAN were applied to identify distinct restaurant segments.


## Methods Implemented

1. **KMeans Clustering**  
2. **Agglomerative Hierarchical Clustering**  
3. **DBSCAN Clustering**

Hyperparameter tuning was performed using silhouette scores to find optimal parameters.

---

## Evaluation Metrics

- **Silhouette Score**: Measures cluster cohesion and separation.
- Other clustering validation techniques and business impact analysis were also discussed.

---

## Results

- Visualizations using PCA for cluster projections.
- Dendrogram for hierarchical clustering visualization.
- Insights on customer segmentation and business recommendations.

---

## How to Use

1. Clone this repo:  
