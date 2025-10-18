---
title: "Lalith Krishna Prakash Parsa"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.45"
  overlay_image: "/assets/banner.png"
  caption: "Ph.D. Applicant in Computer Science | AI • Data Analytics • Machine Learning"
excerpt: >
  AI • Data Analytics • Computer Vision | Academic Portfolio
---

<!-- ===== Profile Section ===== -->
<div style="text-align:center; margin-top:1rem;">
  <img src="{{ '/assets/profile.jpg' | relative_url }}" 
       alt="Profile Photo" 
       class="profile-circle" 
       id="profilePic">
  <h1 style="margin-top:10px;">Lalith Krishna Prakash Parsa</h1>
  <p style="font-size:1.1rem; color:#c7d3d9;">
    Ph.D. Applicant in Computer Science focusing on <strong>AI</strong>, <strong>Data Analytics</strong>, and <strong>Computer Vision</strong>.<br>
    Passionate about developing <em>explainable AI</em> and scalable intelligent data systems.
  </p>
</div>

<!-- Zoom Modal -->
<div id="profileModal">
  <img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Full Profile">
</div>

<script>
document.getElementById("profilePic").onclick = function() {
  document.getElementById("profileModal").classList.add("active");
};
document.getElementById("profileModal").onclick = function() {
  this.classList.remove("active");
};
</script>

---

## 🎯 About Me
I’m **Lalith Krishna Prakash Parsa**, a researcher and developer exploring intersections of **artificial intelligence**, **data analytics**, and **intelligent automation**.  
My work emphasizes scalable pipelines, model interpretability, and real-world data applications.

---

## 🧠 Research & Technical Focus
- Deep Learning and Image Understanding  
- Cloud Data Engineering and Scalable Pipelines  
- Explainable and Ethical AI  
- Visual Intelligence and Computer Vision  
- Data Analytics and Predictive Modeling  

These themes drive both my research and professional projects.

---

## 📘 Featured Research Highlights

### 🔹 Deep Learning–Based Food Recommendation System  
*Capstone Learning Project, Grand Valley State University (Jan 2023 – Apr 2023)*  

- Reimplemented CNN classifier inspired by Food-101 and Recipe1M+ datasets  
- Used TensorFlow and transfer learning (VGG16, ResNet) for food recognition  
- Built Flask-based image recommender for personalized nutrition  

---

### 🔹 Card-less ATM with Biometric Image Input  
*Undergraduate Final Year Project, CVR College of Engineering (Aug 2018 – May 2019)*  

- Developed facial-recognition authentication using OpenCV and TensorFlow  
- Combined biometric verification + PIN entry for dual-factor security  

---

### 🔹 Obstacle Detection for Autonomous Driving using YOLOv5  
*Independent Learning Project (Mar 2022 – Jul 2022)*  

- Practiced YOLOv5 object detection on COCO and BDD100K datasets  
- Deployed to Raspberry Pi and evaluated inference speed vs accuracy  

---

## 📊 Data Analytics & Engineering Projects

### 🌾 Crop Recommendation and Yield Prediction System  
- Reproduced Scikit-learn pipelines from Kaggle datasets for agricultural ML  
- Evaluated models via k-fold cross-validation and feature correlation  

### 💱 Cryptocurrency Analysis and Visualization Dashboard  
- Built R Shiny dashboard for price and volatility analytics using Plotly  

### 🎮 Video Game Sales Analysis Dashboard  
- Designed interactive Tableau dashboard visualizing global game sales  

### 🚇 London Transit Data Warehouse and ELT Pipeline  
- Created Azure Data Factory pipeline and Power BI visualizations for TfL data  

---

## 🔗 Quick Links
- 🔬 [Research Projects]({{ '/research/' | relative_url }})
- 📘 [Publications]({{ '/publications/' | relative_url }})
- 🧑‍🏫 [Teaching]({{ '/teaching/' | relative_url }})
- 📄 [CV]({{ '/cv/' | relative_url }})
- ✉️ [Contact]({{ '/contact/' | relative_url }})

---

<div style="text-align:center; margin-top:2rem; color:#89dce7;">
  © 2025 Lalith Krishna Prakash Parsa | Academic Portfolio
</div>
