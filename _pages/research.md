---
title: "Research and Technical Projects"
layout: single
permalink: /research/
author_profile: false
---

## 🧠 AI & COMPUTER VISION RESEARCH

### Deep Learning–Based Food Recommendation System  
**Capstone Learning Project, Grand Valley State University**  
*Jan 2023 – Apr 2023*

- Reimplemented a CNN-based food image classifier inspired by public research on Food-101 and Recipe1M+ datasets.  
- Used TensorFlow to reproduce feature-embedding and similarity-matching approaches from existing literature.  
- Experimented with transfer learning using pre-trained VGG16 and ResNet models to improve feature accuracy.  
- Processed open food image data to study relationships between visual features and ingredient metadata.  
- Applied cosine-similarity scoring to compare embeddings and group visually similar dishes.  
- Built a lightweight Flask app to test interactive food image queries and display predicted results.  
- Documented experiments, hyperparameter tuning, and model comparison results for evaluation.  
- Focused on understanding how deep visual representations support personalized food recommendations.  

---

### Card-less ATM with Biometric Image Input  
**Undergraduate Final Year Project, CVR College of Engineering**  
*Aug 2018 – May 2019*

- Implemented a facial-recognition-based ATM authentication prototype referencing open biometric research.  
- Used OpenCV and TensorFlow to experiment with Haar Cascade and CNN models for real-time facial detection.  
- Combined biometric verification with PIN entry for secure dual-factor authentication.  
- Preprocessed captured images to normalize brightness and detect tampering under varied lighting.  
- Evaluated system behavior using test datasets from public facial image repositories.  
- Conducted small-scale trials to observe false acceptance and rejection rates.  
- Integrated a local database for offline verification and faster response.  
- Focused on image-based identity verification in financial applications.  

---

### Obstacle Detection for Autonomous Driving using YOLOv5  
**Independent Learning Project**  
*Mar 2022 – Jul 2022*

- Practiced implementing YOLOv5 object detection using open datasets (BDD100K, COCO).  
- Studied model configuration and retraining processes from the official YOLOv5 repository.  
- Experimented with bounding-box tuning, confidence thresholds, and anchor-box optimization.  
- Integrated OpenCV for frame-by-frame video processing and real-time inference.  
- Evaluated speed and accuracy differences between small and medium YOLOv5 models.  
- Deployed to Raspberry Pi to study computational constraints on edge devices.  
- Logged precision-recall metrics and FPS benchmarks under variable lighting.  
- Completed end-to-end workflow from dataset labeling to embedded inference.  

---

## 📊 DATA ANALYTICS & ENGINEERING PROJECTS

### Crop Recommendation and Yield Prediction System  
**Independent Learning Project | Python, Scikit-learn (2023)**

- Reproduced open-source crop-recommendation workflows using Kaggle agricultural datasets.  
- Compared Decision Tree, Random Forest, and Logistic Regression models for crop suitability.  
- Applied correlation analysis to interpret how soil pH, rainfall, and temperature affect yield.  
- Conducted k-fold cross-validation and confusion matrix evaluation.  
- Created visualizations with Matplotlib and Seaborn to explore productivity variations.  
- Implemented preprocessing steps such as outlier removal and normalization.  
- Built a CLI for entering soil parameters and generating predictions.  
- Explored practical supervised learning on structured agricultural data.  

---

### Cryptocurrency Analysis and Visualization Dashboard  
**Learning Project | R, Shiny, Plotly (2023)**

- Followed public R Shiny tutorials using CoinMarketCap APIs and Kaggle datasets.  
- Cleaned daily price and volume data with dplyr and converted to time-series using xts.  
- Computed moving averages and volatility indicators replicating published crypto-trend analyses.  
- Built multi-tab interactive dashboards showing market capitalization, volume, and correlations.  
- Added Plotly for interactive coin-to-coin comparison and date filtering.  
- Optimized reactive expressions to improve dashboard responsiveness.  
- Implemented filters and download options for analytical snapshots.  
- Gained hands-on experience with R-based financial visualization.  

---

### Netflix User Preferences and Content Trends  
**Coursework Project | Python, Pandas, K-Means (2022)**

- Used Netflix dataset for exploratory data analysis and unsupervised clustering.  
- Cleaned metadata (genre, release year, ratings) for consistency.  
- Applied K-Means and PCA for audience segmentation.  
- Visualized trends with bar charts and heatmaps.  
- Correlated genre frequency and user ratings.  
- Automated analysis pipelines using modular scripts.  
- Evaluated cluster quality using silhouette scores.  

---

### Video Game Sales Analysis Dashboard  
**Practice Project | Tableau, Excel (2022)**

- Processed global video game sales data from Kaggle in Excel.  
- Built Tableau dashboards highlighting publishers, genres, and yearly trends.  
- Designed calculated fields for cumulative revenue and platform share.  
- Implemented interactive filters by region, year, and genre.  
- Compared global vs. regional performance trends for market insights.  
- Focused on Tableau and Excel data-prep best practices.  

---

### London Transit Data Warehouse and ELT Pipeline Setup  
**Learning Experiment | Azure Data Factory, SQL, Python (2021)**

- Designed ELT pipeline using Transport for London datasets.  
- Configured Azure Data Factory for extraction and staging.  
- Wrote Python scripts for validation and schema enforcement.  
- Modeled a star-schema warehouse with dimension and fact tables.  
- Implemented incremental load refresh cycles.  
- Queried with SQL to analyze ridership and on-time performance.  
- Built Power BI dashboards to visualize utilization and delays.  
