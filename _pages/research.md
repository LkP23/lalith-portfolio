---
title: "Research and Projects"
layout: single
permalink: /research/
---

# 🔬 Research & Projects

This section presents my end-to-end research and technical projects across AI, Computer Vision, Data Analytics, and Cloud Data Engineering.  
Each card links theory, methodology, and applied work. Hover over each for quick insight.

<div class="projects-grid">

<!-- PROJECT 1 -->
<div class="project-card">
  <img src="/assets/projects/p1.jpg" alt="Deep Learning Food Recommendation">
  <div class="project-card-content">
    <h3>Deep Learning–Based Food Recommendation System</h3>
    <p><b>Grand Valley State University (Jan 2023 – Apr 2023)</b></p>
    <p>
    Designed and implemented a CNN-based food-image classification pipeline using <b>Food-101</b> and <b>Recipe1M+</b> datasets.  
    Reproduced published architectures to learn transferable visual embeddings linking ingredients and appearance.  
    Explored <b>transfer learning</b> with VGG16 and ResNet50 to balance accuracy and training cost.  
    Built an interactive <b>Flask</b> interface for live image queries and similarity-based dish retrieval.  
    Performed comparative evaluation on feature vectors using <b>cosine similarity</b> and t-SNE visualization.  
    Outcome: demonstrated that deep convolutional embeddings can represent complex culinary relationships, laying groundwork for personalized nutrition systems.
    </p>
    <p><b>Keywords:</b> TensorFlow, CNN, Transfer Learning, Flask App, Food Recommender</p>
  </div>
</div>

<!-- PROJECT 2 -->
<div class="project-card">
  <img src="/assets/projects/p2.jpg" alt="Card-less ATM Biometric">
  <div class="project-card-content">
    <h3>Card-less ATM with Biometric Image Input</h3>
    <p><b>CVR College of Engineering (2018 – 2019)</b></p>
    <p>
    Built a prototype <b>biometric ATM authentication</b> system integrating <b>OpenCV</b> face detection with <b>TensorFlow CNN</b> recognition.  
    Implemented dual-factor authentication (facial verification + PIN).  
    Applied <b>brightness normalization</b> and tamper detection to handle variable lighting.  
    Conducted experimental trials using public datasets to measure <b>false acceptance / rejection rates</b>.  
    Developed an offline-capable local database for quick verification and resilience.  
    Demonstrated practical feasibility of <b>image-based secure access</b> in low-resource banking environments.
    </p>
    <p><b>Keywords:</b> OpenCV, TensorFlow, Face Recognition, FinTech Security, Dual-Factor Auth</p>
  </div>
</div>

<!-- PROJECT 3 -->
<div class="project-card">
  <img src="/assets/projects/p3.jpg" alt="YOLOv5 Obstacle Detection">
  <div class="project-card-content">
    <h3>Obstacle Detection for Autonomous Driving using YOLOv5</h3>
    <p><b>Independent Learning Project (2022)</b></p>
    <p>
    Implemented an end-to-end <b>object detection</b> workflow for road scenes using <b>YOLOv5</b> on <b>COCO</b> and <b>BDD100K</b> datasets.  
    Re-trained detection heads to improve small-object accuracy.  
    Tuned anchor boxes and <b>confidence thresholds</b> to evaluate precision–recall trade-offs.  
    Integrated <b>OpenCV</b> for frame-wise inference and video overlay.  
    Deployed model to a <b>Raspberry Pi 4</b> for edge performance testing (≈18 FPS at 416×416).  
    Results highlighted computational constraints and parameter trade-offs crucial for embedded AI in autonomous vehicles.
    </p>
    <p><b>Keywords:</b> YOLOv5, OpenCV, Edge AI, Raspberry Pi, Autonomous Systems</p>
  </div>
</div>

<!-- PROJECT 4 -->
<div class="project-card">
  <img src="/assets/projects/p4.jpg" alt="Crop Recommendation">
  <div class="project-card-content">
    <h3>Crop Recommendation and Yield Prediction System</h3>
    <p><b>Independent Project (2023)</b></p>
    <p>
    Implemented supervised learning models using <b>Scikit-learn</b> on agricultural datasets from Kaggle to recommend optimal crops based on environmental conditions.  
    Compared <b>Decision Tree</b>, <b>Random Forest</b>, and <b>Logistic Regression</b> algorithms using k-fold validation.  
    Analyzed <b>soil pH, rainfall, temperature</b>, and nutrient parameters to interpret yield influence.  
    Created feature-importance visualizations and correlation heatmaps using <b>Seaborn</b>.  
    Outcome: data-driven framework for precision agriculture decision-support.
    </p>
    <p><b>Keywords:</b> Scikit-learn, Agriculture ML, Data Visualization, Predictive Modeling</p>
  </div>
</div>

<!-- PROJECT 5 -->
<div class="project-card">
  <img src="/assets/projects/p5.jpg" alt="Crypto Dashboard">
  <div class="project-card-content">
    <h3>Cryptocurrency Analysis and Visualization Dashboard</h3>
    <p><b>Learning Project (2023)</b></p>
    <p>
    Developed an interactive <b>R Shiny</b> dashboard connecting live data from the <b>CoinMarketCap API</b>.  
    Processed daily price and volume data using <b>dplyr</b> and converted to time-series via <b>xts</b>.  
    Calculated <b>moving averages, volatility indices, and correlations</b> across major cryptocurrencies.  
    Integrated <b>Plotly</b> for zoomable and filterable time-series plots.  
    Enhanced dashboard responsiveness through optimized reactive expressions.  
    Purpose: demonstrate analytical storytelling through reproducible R-based visualization.
    </p>
    <p><b>Keywords:</b> R Shiny, Plotly, Time-Series, Financial Analytics</p>
  </div>
</div>

<!-- PROJECT 6 -->
<div class="project-card">
  <img src="/assets/projects/p6.jpg" alt="Netflix Trends">
  <div class="project-card-content">
    <h3>Netflix User Preferences and Content Trends</h3>
    <p><b>Coursework Project (2022)</b></p>
    <p>
    Conducted unsupervised clustering on global Netflix content metadata using <b>Pandas</b> and <b>K-Means</b>.  
    Cleaned categorical features (genre, release year, rating) and reduced dimensions with <b>PCA</b>.  
    Visualized genre frequency, regional popularity, and temporal evolution through heatmaps and bar plots.  
    Evaluated cluster validity using silhouette analysis.  
    Automated data refresh scripts for continued monitoring of user preferences.
    </p>
    <p><b>Keywords:</b> K-Means, PCA, Pandas, Entertainment Analytics</p>
  </div>
</div>

<!-- PROJECT 7 -->
<div class="project-card">
  <img src="/assets/projects/p7.jpg" alt="Video Game Sales Dashboard">
  <div class="project-card-content">
    <h3>Video Game Sales Analysis Dashboard</h3>
    <p><b>Practice Project (2022)</b></p>
    <p>
    Cleaned and normalized a global video-game sales dataset using <b>Excel</b> preprocessing.  
    Built interactive <b>Tableau dashboards</b> comparing regional and platform trends.  
    Implemented calculated fields for <b>revenue share</b> and cumulative growth.  
    Designed filters for region, year, and genre, enabling dynamic exploration.  
    Provided actionable insight into publisher market cycles and genre longevity.
    </p>
    <p><b>Keywords:</b> Tableau, Excel, Data Visualization, Market Analytics</p>
  </div>
</div>

<!-- PROJECT 8 -->
<div class="project-card">
  <img src="/assets/projects/p8.jpg" alt="London Transit ELT Pipeline">
  <div class="project-card-content">
    <h3>London Transit Data Warehouse and ELT Pipeline</h3>
    <p><b>Azure Data Factory / SQL / Python (2021)</b></p>
    <p>
    Followed Microsoft open-data case studies to design an <b>ELT pipeline</b> using <b>Transport for London</b> datasets.  
    Configured <b>Azure Data Factory</b> pipelines for automated extraction and staging.  
    Validated data with <b>Python scripts</b> enforcing schema integrity.  
    Modeled a <b>star schema</b> warehouse with route, station, and schedule dimensions.  
    Linked <b>Power BI</b> for live route-utilization dashboards and on-time performance metrics.  
    Demonstrated proficiency in <b>cloud data engineering</b> and business intelligence integration.
    </p>
    <p><b>Keywords:</b> Azure Data Factory, Power BI, SQL, ETL/ELT, Cloud Engineering</p>
  </div>
</div>

</div>

---

## 📎 Summary
This collection reflects a trajectory from foundational computer vision research to applied analytics and cloud engineering — illustrating both <b>theoretical understanding</b> and <b>hands-on implementation</b> across diverse data modalities.
