# 🏹 Javelin Throw Analysis Pipeline

This project provides an end-to-end pipeline for analyzing javelin throw clips using pose landmark data. It detects the throw frame, predicts the throw distance, identifies form inconsistencies, and generates personalized, easy-to-understand feedback for athletes—along with performance visualizations.

---

## 📂 Dataset (📥 Download Required)

Download the  `.mp4` clips from this Google Drive link :

🔗 [Download Smoothed Clips (Google Drive)](https://drive.google.com/drive/folders/17loHe_BBmwHOtwiADoGob76aMN4PZDGK?usp=sharing)

## 📄 Project Report (PDF)

A detailed report is available at the following link:

➡️ [View Javelin Project Report on Google Drive](https://drive.google.com/drive/folders/1kRLx3fwHb8SnliL3av-btBz0UPpuacuK?usp=sharing)

---

## 🚀 Features

- ✅ **Throw Frame Detection** – Automatically locates the throw moment in each clip
- 📏 **Distance Prediction** – Estimates throw distance using a trained GBR model
- ❌ **Error Detection** – Flags technical issues with a form classifier
- 🔍 **Kinematic Metrics** – Lean angle, elbow motion, leg block strength
- 💬 **Natural Language Feedback** – Actionable, emoji-based coaching insights
- 📊 **Visual Summaries** – Matplotlib and Seaborn graphs of key metrics

---

## 🛠 Setup Instructions

### Requirements
- pip install numpy pandas matplotlib seaborn scikit-learn joblib mediapipe 

