# product-recommendation & User Segmentation for E-Commerce

This project simulates a personalized product recommendation system and user behavior analysis for a niche e-commerce platform using **Python, Tableau, and KMeans clustering**. It demonstrates the end-to-end pipeline from **data generation**, **exploratory analysis**, **clustering**, to **recommendation logic** — packaged with intuitive Tableau dashboards.

##  Objective

To build a robust, explainable, and visually interactive **product recommendation system** using **user behavior**, **rating patterns**, and **clustering techniques** — all with simulated but realistic data.

---

## Tools & Technologies

- **Python**: pandas, scikit-learn, matplotlib, seaborn
- **Tableau**: for interactive dashboards
- **Mockaroo**: to simulate user, product, and rating data
- **KMeans Clustering**: for segmenting user behavior

---

## Dashboard 1: User Behavior & Ratings EDA

A comprehensive analysis of user engagement and ratings activity over time.

### Highlights:
- **30-Day Rolling Ratings Trend**
- **Total Ratings per signup year**
- **Ratings by Hour of Day**
- **User Retention Snapshot** (% of users with multiple ratings(more than 1))

---

## Dashboard 2: Product Recommendations by Cluster

An intelligent clustering-based recommendation system designed to personalize product recommendations per user segment.

### Highlights:
- **User Segmentation via KMeans (k=5)**
- **Number of Users per Cluster**
- **Top 5 Recommended Products per Cluster**
- **Cluster Label Summaries**

| Cluster | Behavior Summary                        |
|---------|------------------------------------------|
| 0       | Moderate activity, balanced ratings       |
| 1       | High activity, consistent raters          |
| 2       | Sporadic raters, lower average ratings    |
| 3       | Highly active and engaged                 |
| 4       | High raters, fewer products, generous     |

---
**Dashboard Link:**

https://public.tableau.com/app/profile/arya.raghuveer.mane/viz/Product_recommendation_visualization/BehavioralInsightsfromUserRatings?publish=yes

---
## Datasets Used

- `user_final_data.csv`: 5000 users with sign-up data and demographics
- `final_ratings_cleaned.csv`: ~74,000 ratings with timestamps
- `products.csv`: Simulated product catalog
- `labeled_clutering_users.csv`: KMeans cluster assignments per user

---

## How It Works

1. **Simulated Data Generation**: Using Mockaroo and Python to generate realistic datasets
2. **EDA**: Uncover trends, engagement, and retention behavior
3. **Clustering**: Segment users based on behavioral metrics (ratings count, gaps, variance)
4. **Recommendation**: Recommend products popular within each cluster
5. **Visualization**: Build two interactive Tableau dashboards

---

## Key Insights

- Most active users show tighter rating variance and shorter time gaps
- Cluster 3 represents power users with frequent, high-volume activity
- Retention rate (users rating more than once) is ~45% — suggesting moderate long-term engagement
- Product recommendations can be fine-tuned per cluster to improve targeting

---

## Future Improvements
- Incorporate user location and category preferences
- Deploy via Streamlit for a live demo interface

---

## Author

**Arya Mane**  
M.S. in Information Technology & Management  
University of Texas at Dallas


