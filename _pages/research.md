---
title: "Research and Projects"
layout: single
permalink: /research/
---

# 🔬 Research and Projects

My research bridges **Artificial Intelligence**, **Computer Vision**, and **Data Analytics** with a focus on reproducible experiments, real-world datasets, and interpretability.  
The following sections detail my core academic and learning projects, including deliverables, experimentation notes, and evaluation outcomes.

---

## 🧠 AI & COMPUTER VISION RESEARCH

### Deep Learning–Based Food Recommendation System
<img src="/assets/projects/p1.jpg" alt="Deep Learning–Based Food Recommendation System" class="project-image">

**Capstone Learning Project, Grand Valley State University**  
**Duration:** Jan 2023 – Apr 2023  

- Reimplemented a **CNN-based food image classifier** inspired by public research on Food-101 and Recipe1M+ datasets.  
- Used **TensorFlow** to reproduce feature-embedding and similarity-matching approaches from existing literature.  
- Experimented with **transfer learning** using pre-trained VGG16 and ResNet models to improve feature accuracy.  
- Processed open food image data to study the relationship between visual features and ingredient metadata.  
- Applied **cosine-similarity scoring** to compare embeddings and group visually similar dishes.  
- Built a lightweight **Flask** application to test interactive food image queries and display predicted results.  
- Documented training experiments, hyperparameter tuning, and model comparison results for learning evaluation.  
- Project outcome focused on understanding how **deep visual representations** can support personalized food recommendation.

---

### Card-less ATM with Biometric Image Input
<img src="/assets/projects/p2.jpg" alt="Card-less ATM with Biometric Image Input" class="project-image">

**Undergraduate Final Year Project, CVR College of Engineering**  
**Duration:** Aug 2018 – May 2019  

- Implemented a **facial-recognition-based ATM authentication** prototype referencing open research on biometric security.  
- Used **OpenCV** and **TensorFlow** to experiment with Haar Cascade and CNN models for real-time facial detection.  
- Combined biometric verification with PIN entry for **secure dual-factor authentication**.  
- Preprocessed captured images to normalize brightness and detect tampering under varied lighting conditions.  
- Evaluated system behavior using test datasets from public facial image repositories.  
- Conducted small-scale trials to observe **false-acceptance** and **rejection** rates under realistic conditions.  
- Integrated local database for offline verification and faster response during simulated transactions.  
- Project emphasized conceptual understanding of **image-based identity verification** in financial applications.

---

### Obstacle Detection for Autonomous Driving using YOLOv5
<img src="/assets/projects/p3.jpg" alt="Obstacle Detection for Autonomous Driving" class="project-image">

**Independent Learning Project**  
**Duration:** Mar 2022 – Jul 2022  

- Practiced implementing **YOLOv5 object detection** using open datasets such as BDD100K and COCO for road scenes.  
- Studied model configuration and retraining processes from the official YOLOv5 GitHub repository.  
- Experimented with **bounding-box tuning**, confidence thresholds, and anchor-box optimization to observe detection trade-offs.  
- Integrated **OpenCV** for frame-by-frame video processing and real-time inference testing.  
- Evaluated inference speed and accuracy differences between small and medium YOLOv5 variants.  
- Deployed the model on **Raspberry Pi** hardware to understand computational constraints of edge devices.  
- Logged **precision-recall metrics** and FPS benchmarks to interpret performance under variable lighting.  
- Focused on grasping **end-to-end workflow** from dataset labeling to embedded inference in autonomous systems.

---

## 📊 DATA ANALYTICS & ENGINEERING PROJECTS

### Crop Recommendation and Yield Prediction System
<img src="/assets/projects/p4.jpg" alt="Crop Recommendation and Yield Prediction" class="project-image">

**Independent Learning Project — Python / Scikit-learn**  
**Year:** 2023  

- Reproduced open-source crop-recommendation workflows from public Kaggle agricultural datasets.  
- Used **Scikit-learn** to compare decision-tree, random-forest, and logistic-regression models for crop suitability.  
- Applied **feature-correlation analysis** to interpret how soil pH, rainfall, and temperature influence yield.  
- Conducted model evaluation with **k-fold cross-validation** and confusion-matrix reporting.  
- Created visualizations in **Matplotlib / Seaborn** to explore regional productivity variations.  
- Practiced preprocessing steps such as outlier removal and normalization for numeric consistency.  
- Packaged the workflow into a simple **CLI** for entering soil parameters and viewing predictions.  
- Objective was to understand **supervised-learning application** to structured agricultural data.

---

### Cryptocurrency Analysis and Visualization Dashboard
<img src="/assets/projects/p5.jpg" alt="Cryptocurrency Dashboard" class="project-image">

**Learning Project — R / Shiny / Plotly**  
**Year:** 2023  

- Followed public **R Shiny dashboard** tutorials using open CoinMarketCap API and Kaggle crypto datasets.  
- Cleaned daily price and volume data with **dplyr** and converted to time-series using **xts**.  
- Computed **moving averages** and volatility indicators to replicate published crypto-trend analyses.  
- Built multi-tab interactive dashboard showing market capitalization, volume, and correlation heatmaps.  
- Added **Plotly interactivity** for date-range selection and coin-to-coin comparison.  
- Optimized reactive expressions to improve dashboard responsiveness under frequent refresh.  
- Tested user-driven filters and download features for analytical snapshots.  
- Goal was to gain **hands-on experience in R-based financial data visualization**.

---

### Netflix User Preferences and Content Trends
<img src="/assets/projects/p6.jpg" alt="Netflix User Preferences and Content Trends" class="project-image">

**Coursework Practice Project — Python / Pandas / K-Means**  
**Year:** 2022  

- Used public Kaggle **Netflix dataset** to practice exploratory data analysis and unsupervised clustering.  
- Cleaned metadata fields such as genre, release year, and viewer ratings for uniformity.  
- Implemented **K-Means clustering** and **PCA** to replicate common audience-segmentation studies.  
- Generated bar charts and heatmaps to visualize regional and temporal viewing trends.  
- Investigated correlations between **genre frequency** and **user-rating averages**.  
- Automated analysis steps through modular Python scripts for re-execution with updated data.  
- Evaluated cluster quality using **silhouette scores** and explained results through visual summaries.  
- Learned **end-to-end pipeline creation** for consumer-behavior analytics using open datasets.

---

### Video Game Sales Analysis Dashboard
<img src="/assets/projects/p7.jpg" alt="Video Game Sales Dashboard" class="project-image">

**Practice Project — Tableau / Excel**  
**Year:** 2022  

- Downloaded global **video-game sales dataset** from Kaggle and prepared it for Tableau visualization.  
- Cleaned and normalized sales records in **Excel** addressing missing values and inconsistent regions.  
- Recreated standard industry dashboards highlighting top publishers, genres, and yearly trends.  
- Implemented calculated fields for **cumulative revenue** and platform market share.  
- Designed **interactive filters** for region, year, and genre to mirror professional BI dashboards.  
- Compared global vs. regional performance trends to observe platform dominance cycles.  
- Reviewed dashboard design for clarity and accessibility following Tableau Public examples.  
- Exercise focused on mastering **Excel preprocessing** and **Tableau visualization workflow**.

---

### London Transit Data Warehouse and ELT Pipeline Setup
<img src="/assets/projects/p8.jpg" alt="London Transit Data Warehouse" class="project-image">

**Learning Experiment — Azure Data Factory / SQL / Python**  
**Year:** 2021  

- Followed Microsoft open-data tutorials to design an **ELT pipeline** using Transport for London (TfL) datasets.  
- Configured **Azure Data Factory** for scheduled extraction and staging of ridership and schedule data.  
- Implemented data-validation scripts in **Python** for schema enforcement and null-value handling.  
- Modeled a **star-schema warehouse** with route, station, and schedule dimension tables.  
- Practiced incremental-load configuration to simulate production data-refresh cycles.  
- Queried warehouse tables in **SQL** to analyze daily ridership and on-time performance.  
- Linked **Power BI** to visualize route utilization, delay patterns, and refresh-latency metrics.  
- Project objective was to learn **practical cloud-based data-engineering and visualization integration**.
