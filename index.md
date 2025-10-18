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

<!-- ===============================
     PROFILE SECTION
==================================-->
<div style="text-align:center; margin-top:1.5rem;">
  <div style="display:inline-block; text-align:center;">
    <img src="{{ '/assets/profile.jpg' | relative_url }}" 
         alt="Profile Photo" 
         class="profile-circle" 
         id="profilePic"
         style="width:140px; height:140px; border-radius:50%; border:3px solid #00b4b6; object-fit:cover; box-shadow:0 0 15px rgba(0,180,186,0.5);">
    <h1 style="margin-top:12px; color:#5de3e8;">Lalith Krishna Prakash Parsa</h1>
    <p style="font-size:1.1rem; color:#d8e8ea;">
      Ph.D. Applicant in Computer Science focusing on <strong>AI</strong>, 
      <strong>Data Analytics</strong>, and <strong>Computer Vision</strong>.<br>
      Passionate about developing <em>explainable AI</em> and scalable intelligent systems.
    </p>
  </div>
</div>

<!-- ===============================
     IMAGE ZOOM MODAL
==================================-->
<div id="profileModal" style="display:none; position:fixed; z-index:9999; left:0; top:0; width:100%; height:100%; background:rgba(0,0,0,0.9); justify-content:center; align-items:center;">
  <img src="{{ '/assets/profile.jpg' | relative_url }}" 
       alt="Full Profile" 
       style="max-width:90%; border-radius:10px; box-shadow:0 0 25px rgba(0,200,210,0.5);">
</div>

<script>
document.getElementById("profilePic").onclick = function() {
  document.getElementById("profileModal").style.display = "flex";
};
document.getElementById("profileModal").onclick = function() {
  this.style.display = "none";
};
</script>

---

## 🎯 About Me
I’m **Lalith Krishna Prakash Parsa**, a researcher exploring intersections of **artificial intelligence**, **data analytics**, and **intelligent automation**.  
My work emphasizes scalable pipelines, model interpretability, and real-world data applications.

---

## 🧠 Research & Technical Focus
- Deep Learning and Image Understanding  
- Cloud Data Engineering and Scalable Pipelines  
- Explainable and Ethical AI  
- Visual Intelligence and Computer Vision  
- Data Analytics and Predictive Modeling  

---

## 📘 Featured Research Highlights

### 🔹 Deep Learning–Based Food Recommendation System  
*Capstone Project, Grand Valley State University (Jan 2023 – Apr 2023)*  
- Reimplemented CNN classifier using Food-101 and Recipe1M+ datasets.  
- Applied TensorFlow transfer learning (VGG16, ResNet).  
- Built Flask-based image recommender for personalized nutrition.

---

### 🔹 Card-less ATM with Biometric Image Input  
*Undergraduate Final Year Project, CVR College of Engineering (Aug 2018 – May 2019)*  
- Developed facial-recognition authentication using OpenCV and TensorFlow.  
- Combined biometric verification + PIN entry for dual-factor security.

---

### 🔹 Obstacle Detection for Autonomous Driving using YOLOv5  
*Independent Learning Project (Mar 2022 – Jul 2022)*  
- Implemented YOLOv5 object detection for road scenes (COCO, BDD100K datasets).  
- Deployed to Raspberry Pi and evaluated real-time inference performance.

---

## 📊 Data Analytics & Engineering Projects

### 🌾 Crop Recommendation and Yield Prediction  
- Reproduced Scikit-learn pipelines using Kaggle agricultural datasets.  
- Evaluated Decision Tree, Random Forest, and Logistic Regression models.

### 💱 Cryptocurrency Analysis Dashboard  
- Built R Shiny dashboard visualizing price, volatility, and market cap trends.

### 🎮 Video Game Sales Dashboard  
- Designed Tableau dashboard highlighting publisher, genre, and regional trends.

### 🚇 London Transit Data Warehouse  
- Built Azure Data Factory ETL and Power BI visualizations for TfL analytics.

---

## 🔗 Quick Links
- 🔬 [Research Projects]({{ '/research/' | relative_url }})
- 📘 [Publications]({{ '/publications/' | relative_url }})
- 🧑‍🏫 [Teaching]({{ '/teaching/' | relative_url }})
- 📄 [CV]({{ '/cv/' | relative_url }})
- ✉️ [Contact]({{ '/contact/' | relative_url }})

---

<div style="text-align:center; margin-top:2rem; color:#88e3e7;">
  © 2025 Lalith Krishna Prakash Parsa | Academic Portfolio
</div>
