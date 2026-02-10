# Gaming Profile Analytics & Churn Modeling (End-to-End)

This project delivers an end-to-end **Gaming Analytics + Machine Learning** solution focused on player behavior analysis, segmentation, and churn prediction using interactive dashboards and ML models.

The workflow covers data preparation, exploratory analysis, player segmentation, churn modeling, and model evaluation, supported by Looker Studio dashboards and Google Colab notebooks.

---

## Project Overview

**Objectives**
- Analyze global gaming platform performance
- Segment players based on engagement behavior
- Identify dormant and churn-risk players
- Build and evaluate a churn prediction model
- Deliver business-ready insights via dashboards

**Key Techniques**
- SQL-based data modeling
- Exploratory Data Analysis (EDA)
- K-Means clustering for player segmentation
- Supervised churn prediction modeling
- Model evaluation and calibration
- Interactive dashboard design

---

## Dashboard Pages & Visual Assets

### 01. Global Platform Snapshot
High-level overview of the gaming ecosystem including total games, revenue, publishers, players, and geographic coverage.

![Global Platform Snapshot](images/01_global_platform_snapshot.png)

---

### 02. Global Platform Snapshot – Detailed View
Deeper exploration of platform performance with country-level and temporal breakdowns.

![Global Platform Snapshot Detail](images/02_global_platform_snapshot_detail.png)

---

### 03. Player Segmentation & Churn Analysis
Overview of player segments, engagement levels, and churn distribution.

![Player Segmentation & Churn Analysis](images/03_player_segmentation_churn_analysis.png)

---

### 04. Game & Revenue Analysis
Revenue concentration, top-performing games, and engagement-driven revenue insights.

![Game Revenue Analysis](images/04_game_revenue_analysis.png)

---

### 05. Game & Genre Analysis
Distribution of games and pricing across genres.

![Game Genre Analysis](images/05_game_genre_analysis.png)

---

### 06. Platform Comparison: Game & Pricing
Comparison of platforms (PlayStation, Steam) in terms of game volume, pricing strategy, and release trends.

![Platform Comparison](images/06_platform_comparison_game_pricing.png)

---

### 07. Player Segmentation (Machine Learning)
K-Means clustering results defining player segments based on engagement behavior.

![Player Segmentation ML](images/07_player_segmentation_ml.png)

---

### 08. Dormant Segment Analysis
Behavioral characteristics and early warning signals for dormant players.

![Dormant Segment Analysis](images/08_dormant_segment_analysis.png)

---

### 09. Churn Modeling & Performance
Evaluation of churn prediction performance using ROC curves and confusion matrices.

![Churn Model Performance](images/09_churn_model_performance.png)

---

### 10. Feature Impact & Model Calibration
Feature importance analysis and risk score calibration for churn prediction.

![Churn Feature Impact & Calibration](images/10_churn_feature_impact_calibration.png)

---

## Notebooks (Google Colab)

All analysis and modeling steps are reproducible via Google Colab notebooks.

- **End-to-End Gaming Analytics & Churn Modeling**  
  https://colab.research.google.com/github/ilaydagurcan/gaming-profile-analytics-churn-ml/blob/main/notebooks/gaming_profile_analytics_churn_ml.ipynb

---

## Churn Definition

A player is labeled as **churned** if no activity is observed for **60 consecutive days** after the analysis date.  
Churn is defined based on **achievement activity**, not login behavior, to better capture meaningful engagement loss.

---

## Key Outcomes

- Clear identification of high-value and at-risk player segments
- Actionable churn risk signals for re-engagement strategies
- Interpretable churn prediction model with strong recall
- Business-ready dashboards for decision support

---

## Tools & Technologies

- SQL
- Python (Pandas, Scikit-learn, Matplotlib)
- Google Colab
- Looker Studio
- GitHub

---

## Author

**İlayda Gurcan**  
End-to-end analytics, dashboarding, and machine learning implementation.
