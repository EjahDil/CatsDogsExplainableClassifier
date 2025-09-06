# 🐱🐶 Cats vs Dogs Explainable Classifier

This project implements a **binary image classifier** to distinguish between **cats** and **dogs** using the **EfficientNet-B0** architecture.  
Beyond classification, it integrates **explainable AI (XAI)** techniques to provide insights into *how* the model makes its predictions.

---

## 📌 Project Overview
- **Task**: Binary classification — Cat 🐱 vs Dog 🐶  
- **Model**: [EfficientNet-B0](https://arxiv.org/abs/1905.11946), trained from scratch  
- **Explainability Methods**:
  - **Occlusion Sensitivity**
  - **Grad-CAM**
  - **Integrated Gradients**
- **Dataset**: [Kaggle Cats and Dogs Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54765)  
  Released under the *Microsoft Research Data License Agreement*.

---

## 🔍 Explainability Results

### 1. **Occlusion Sensitivity**
Highlights important image patches by systematically covering regions and measuring prediction drops.  
- Cats: Face and body outline most important  
- Dogs: Head, snout, and ears dominate importance  

### 2. **Grad-CAM**
Heatmaps show where the model “looks” when predicting.  
- Cat → eyes, ears, and face  
- Dog → snout and head  

### 3. **Integrated Gradients**
Pixel-level attribution highlights semantically meaningful features.  
- Cat → face and body outline  
- Dog → head and torso  
---

## 🚀 Run Project on your local computer

**Clone this repository**
   ```bash
   git clone https://github.com/EjahDil/CatsDogsExplainableClassifier.git
   cd CatsDogsExplainableClassifier
   ```
