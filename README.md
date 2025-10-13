# Music Recommendation System  | MIT Applied Data Science - AI & Machine Learning 2025
**Music Recommendation Systems**

Built and compared multiple music recommendation systems (popularity, collaborative, content-based, SVD) using user-song play data. Optimized for accuracy, diversity, and cold start—hybrid approach boosts engagement and personalizes music discovery.

**Author:** Austin McCollough

**Program:** MIT Applied Data Science Program, Summer Cohort 2025  

**Date:** August 2025

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-surprise

**Full Report & Code:** [Google Drive - Music Recommendation Systems](https://drive.google.com/drive/folders/1GSBZZzNu1CUkqxx8wOpQ3zrakOhcyB0K?usp=share_link)

## Table of Contents

### Project Overview
### Problem Statement
### Solution Design
### Methodology
### Business Impact
### Implementation Recommendations
### Expected Benefits and Costs
### Risks and Challenges
### Next Steps
### Full Report & Code

## Project Overview 

This project addresses the challenge of surfacing relevant, engaging music for users in today’s crowded digital landscape. Multiple recommendation strategies were explored—popularity-based, collaborative filtering (user-user and item-item), matrix factorization (SVD), clustering, and content-based filtering—to identify the most effective, scalable solution.

## Problem Statement

Digital music platforms struggle with:
Overwhelming choice for users, leading to decision fatigue
Popularity bias and “cold start” issues (new users/songs)
Limited recommendation diversity, reducing discovery and engagement

## Solution Design

Hybrid Recommendation System:
Optimized SVD (Matrix Factorization): Core engine for personalized, accurate recommendations by uncovering latent user/song preferences.
Content-Based Filtering: Uses song metadata (title, artist, album, etc.) to recommend similar tracks, crucial for new users and expanding discovery.
Optional Ensemble Blending: For even greater performance and diversity.

## Methodology

Data Preparation: User-song interaction matrix, song metadata extraction, and feature engineering.

[song_data.csv]
https://drive.google.com/file/d/1hW3UUQjKwMH_THHh3mn_UAoG-gM2Ay-Z/view?usp=share_link


[count_data.csv]
https://drive.google.com/file/d/1G-Z7sACzbH1ziI2nYuGMjoEttGFqsnbW/view?usp=share_link

## Modeling Approaches:
 * Popularity-based baseline
 * User-user and item-item collaborative filtering
 * Matrix factorization (SVD), including hyperparameter tuning
 * Content-based filtering for cold start and diversity
 * Hybrid/ensemble models
### Evaluation Metrics: RMSE, Precision@K, Recall@K, coverage, diversity, and user engagement
### Monitoring: Automated retraining, hyperparameter tuning, and A/B testing for ongoing improvement

## Business Impact

* Drives Engagement: Personalized recommendations increase session length and repeat visits.
* Boosts Retention: Diverse, satisfying discovery reduces churn.
* Promotes Catalog Utilization: Surfaces both mainstream and niche content, maximizing catalog value.
* Supports Marketing: Enables personalized campaigns and targeted promotions.

## Implementation Recommendations

### Deploy the Hybrid System:
 *  Use optimized SVD as the primary engine.
 *  Integrate content-based filtering for cold start and diversity.
 *  Optionally blend models for final ranking.
### Monitor and Continuously Improve:
 *  Track RMSE, Precision@K, Recall@K, coverage, diversity, and engagement.
 *  Automate retraining and tuning as new data is collected.
 *  Run A/B tests to optimize user experience and business KPIs.
### Expand Features and Data:
 *  Add song/user features (genre, lyrics, demographics).
 *  Use implicit feedback (skips, likes, playlist adds).
 *  Build feedback loops for continuous improvement.

### Expected Benefits and Costs

## Benefits:
 * Projected 10–20% increase in user engagement and retention
 * Enhanced promotion of new releases and long-tail content
 * Improved user satisfaction and competitive differentiation
## Costs:
 * Initial investment in development and integration
 * Ongoing operational costs for retraining and monitoring
 * Estimated payback: 6–12 months with moderate retention increases

### Risks and Challenges

* Data Quality & Sparsity: Requires ongoing cleaning and enrichment
* Scalability: Computational demands grow with catalog and user base
* Interpretability: SVD/hybrid models are less transparent; consider explainability tools

### Next Steps

* Explore advanced hybrid/ensemble and deep learning techniques
* Benchmark against industry standards and run user surveys
* Investigate explainability and user control features (“Why was this recommended?”)
* Monitor for model drift and update as user behavior changes

## Full Report & Code

**Access the complete project report, code, and analysis here:**  
 
 [Google Drive - Music Recommendation Systems](https://drive.google.com/drive/folders/1GSBZZzNu1CUkqxx8wOpQ3zrakOhcyB0K?usp=share_link)

**Access all original datasets and supporting resources for this project here:**

 [Google Drive – Datasets & Resources](https://drive.google.com/drive/folders/1Sgwo0CyK8LmC3vMczqx67NaOMOC-SvNk?usp=share_link)



For questions or collaboration inquiries, please reach out via email or connect on GitHub.

[GH:](https://github.com/data-wizard-aus)

E: amcco.datascience@gmail.com

---

**Prepared by Austin McCollough | studio.47 Analytics**  

---
