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
<img src="{{ site.baseurl }}/assets/projects/p1.jpg" alt="Food Recommendation" class="project-image">

- Reimplemented a CNN-based food image classifier inspired by public research on Food-101 and Recipe1M+ datasets.  
- Used TensorFlow to reproduce feature-embedding and similarity-matching approaches from existing literature.  
- Experimented with transfer learning using pre-trained VGG16 and ResNet models to improve feature accuracy.  
- Processed open food image data to study the relationship between visual features and ingredient metadata.  
- Applied cosine-similarity scoring to compare embeddings and group visually similar dishes.  
- Built a lightweight Flask application to test interactive food image queries and display predicted results.  
- Documented training experiments, hyperparameter tuning, and model comparison results for learning evaluation.  
- Focused on understanding how deep visual representations can support personalized food recommendation systems.  

---

### Card-less ATM with Biometric Image Input  
**Undergraduate Final Year Project, CVR College of Engineering**  
*Aug 2018 – May 2019*  
<img src="{{ site.baseurl }}/assets/projects/p2.jpg" alt="Card-less ATM" class="project-image">

- Implemented a facial-recognition-based ATM authentication prototype referencing open research on biometric security.  
- Used OpenCV and TensorFlow to experiment with Haar Cascade and CNN models for real-time facial detection.  
- Combined biometric verification with PIN entry for secure dual-factor authentication.  
- Preprocessed captured images to normalize brightness and detect tampering under varied lighting conditions.  
- Evaluated system behavior using test datasets from public facial image repositories.  
- Conducted small-scale trials to observe false acceptance and rejection rates under realistic conditions.  
- Integrated a local database for offline verification and faster response during simulated transactions.  
- Emphasized conceptual understanding of image-based identity verification in financial applications.  

---

### Obstacle Detection for Autonomous Driving using YOLOv5  
**Independent Learning Project**  
*Mar 2022 – Jul 2022*  
<img src="{{ site.baseurl }}/assets/projects/p3.jpg" alt="YOLOv5 Object Detection" class="project-image">

- Practiced implementing YOLOv5 object detection using open datasets such as BDD100K and COCO for road scenes.  
- Studied model configuration and retraining processes from the official YOLOv5 GitHub repository.  
- Experimented with bounding-box tuning, confidence thresholds, and anchor-box optimization to observe detection trade-offs.  
- Integrated OpenCV for frame-by-frame video processing and real-time inference testing.  
- Evaluated inference speed and accuracy differences between small and medium YOLOv5 variants.  
- Deployed the model on Raspberry Pi hardware to study computational constraints of edge devices.  
- Logged precision-recall metrics and FPS benchmarks to analyze performance under variable lighting.  
- Focused on the full workflow from dataset labeling to embedded inference in autonomous systems.  

---

## 📊 DATA ANALYTICS & ENGINEERING PROJECTS

### Crop Recommendation and Yield Prediction System  
**Independent Learning Project | Python, Scikit-learn (2023)**  
<img src="{{ site.baseurl }}/assets/projects/p4.jpg" alt="Crop Recommendation" class="project-image">

- Reproduced open-source crop-recommendation workflows using Kaggle agricultural datasets.  
- Compared Decision Tree, Random Forest, and Logistic Regression models for crop suitability.  
- Applied feature correlation analysis to interpret how soil pH, rainfall, and temperature affect yield.  
- Conducted k-fold cross-validation and confusion matrix evaluation.  
- Created visualizations with Matplotlib and Seaborn to explore productivity variations.  
- Implemented preprocessing steps such as outlier removal and normalization for numeric consistency.  
- Packaged the workflow into a CLI for entering soil parameters and generating predictions.  
- Explored practical supervised learning for structured agricultural data.  

---

### Cryptocurrency Analysis and Visualization Dashboard  
**Learning Project | R, Shiny, Plotly (2023)**  
<img src="{{ site.baseurl }}/assets/projects/p5.jpg" alt="Crypto Dashboard" class="project-image">

- Followed public R Shiny tutorials using open CoinMarketCap APIs and Kaggle datasets.  
- Cleaned daily price and volume data using dplyr and converted to time-series with xts.  
- Computed moving averages and volatility indicators to replicate published crypto analyses.  
- Built interactive dashboards with multi-tab layout and correlation heatmaps.  
- Added Plotly components for date-range selection and coin comparison.  
- Optimized reactive expressions to improve dashboard responsiveness.  
- Implemented user-driven filters and CSV download features for analytical snapshots.  
- Strengthened expertise in R-based financial data visualization.  

---

### Netflix User Preferences and Content Trends  
**Coursework Project | Python, Pandas, K-Means (2022)**  
<img src="{{ site.baseurl }}/assets/projects/p6.jpg" alt="Netflix Analysis" class="project-image">

- Used public Netflix dataset to practice exploratory data analysis and clustering.  
- Cleaned metadata fields such as genre, release year, and ratings.  
- Applied K-Means and PCA for audience segmentation studies.  
- Visualized viewing trends via bar charts and heatmaps.  
- Correlated genre frequency with average user ratings.  
- Automated analysis through modular scripts for reproducibility.  
- Evaluated cluster quality using silhouette scores and PCA variance analysis.  

---

### Video Game Sales Analysis Dashboard  
**Practice Project | Tableau, Excel (2022)**  
<img src="{{ site.baseurl }}/assets/projects/p7.jpg" alt="Video Game Dashboard" class="project-image">

- Processed global video game sales data from Kaggle using Excel preprocessing.  
- Built interactive Tableau dashboards with regional and temporal filters.  
- Analyzed publisher, genre, and platform dominance trends.  
- Designed calculated fields for cumulative revenue and market share visualization.  
- Focused on professional BI dashboard creation workflow.  

---

### London Transit Data Warehouse and ELT Pipeline  
**Learning Experiment | Azure Data Factory, SQL, Python (2021)**  
<img src="{{ site.baseurl }}/assets/projects/p8.jpg" alt="London Transit" class="project-image">

- Designed ELT pipeline using Transport for London datasets.  
- Configured Azure Data Factory for automated data extraction and staging.  
- Wrote Python scripts for validation and schema enforcement.  
- Modeled star-schema warehouse with dimension and fact tables.  
- Implemented incremental load simulation for near real-time refreshes.  
- Queried warehouse with SQL for ridership and performance analytics.  
- Built Power BI dashboards to visualize route utilization and delay patterns.  
