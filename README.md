---
title: X_ray-Analysis (Pneumonia test)(flask app)
emoji: 🐱🐇
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
---

# 🐱🐇  X_ray-Analysis (Pneumonia test)(flask app)

This Space hosts a **Flask-based image classifier** that predicts whether an uploaded image contains a **normal** or a **Pneumic patient**.



## 🚀 How it Works
- You upload an image.
- The image is preprocessed and passed through the CNN.
- The model outputs:
  - predicted class 
  - probability score
  




## 🔧 Tech Stack
- Python + Flask
- PyTorch
- Docker
- Hugging Face Spaces

## ▶️ Running Locally
pip install -r requirements.txt
python main.py


## 🐳 Docker Build (Hugging Face)
The Space uses a custom Dockerfile to run Flask on port **7860**.

---



