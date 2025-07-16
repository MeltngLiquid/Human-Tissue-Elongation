# 🧠 Human Tissue Elongation Prediction using CNNs

This project uses a Convolutional Neural Network (CNN) to predict **tissue elongation** from medical images by detecting key anatomical points. It’s a compact, efficient model that quantifies soft-tissue deformation — potentially useful for diagnostic or biomechanical analysis.

> 📍 *Developed under the guidance of a faculty advisor at IIT Hyderabad as part of an academic research initiative.*

---

### 🚀 What this project does
- Takes input medical images (RGB format)
- Locates two anatomical points of interest
- Predicts their positions and calculates elongation
- Trained on synthetically generated data (see below)
- Uses TensorFlow & Keras with image augmentation

---

### 🧪 Dataset
The dataset used for training was **generated synthetically** to simulate tissue deformation with labeled anatomical landmarks.

🔧 **Want to try it yourself?**  
A separate script is included to help you generate your own dataset — complete with image generation and labeled keypoints in CSV format.

---

### 🏗️ Why I built this
I wanted to explore how deep learning could quantify changes in human tissues — not just classify or segment them. This project is a step toward **building interpretable models for clinical workflows**. Instead of detecting diseases directly, it shows how AI can help measure physical deformations automatically.

---

### ⚙️ Tech Stack
- Python, TensorFlow, Keras
- CNNs (Conv2D → MaxPooling → Dense layers)
- Data Augmentation (rotation, zoom, flip, etc.)
- CSV-based keypoint labels
- Synthetic image generation pipeline

---

### 📈 Results
- Prediction accuracy: **~95% on test data**
- Robust inference on unseen tissue configurations
- Lightweight model, fast to train and deploy

---

### 🧠 Sample Input vs Output (Demo GIF coming soon)
Imagine a muscle ultrasound-like image as input → The model identifies 2 anchor points → Outputs a stretch vector or elongation measure.

---

### 🤝 Contribution
This is a single-author academic project, but PRs are welcome for improvements or enhancements!

---

### 📁 How to Run
1. Clone the repo  
2. Generate your dataset using the included script (or use the provided one)  
3. Place your images and `labels.csv` inside `datasetfortwotwod/`  
4. Run the notebook: `Human tissue elongation.ipynb`  
5. Trained model will output elongation predictions

---

