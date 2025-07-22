# Semantic Segmentation with Depth Estimation

This project performs semantic segmentation on images using depth estimation techniques with a pretrained transformer-based model.
## 📌 Features

- 🌄 Load any RGB image
- 🔍 Estimate per-pixel depth using the `DPT-Large` model from Hugging Face
- 🎨 Visualize both original image and depth map side by side
- 📚 Google Colab ready — no GPU setup needed locally

---

## 🧠 What is Semantic Segmentation?

Semantic segmentation is the process of labeling each pixel in an image with a class.  
In this project, **depth estimation** is used as a pre-step to help understand the spatial structure of the image before segmentation.

## 🔍 Overview

- Uses Intel's `DPT-Large` transformer model from Hugging Face
- Performs depth estimation and segmentation
- Suitable for research and demo purposes

## 📁 Project Structure


## 📦 Dependencies

Install all required packages:

```bash
pip install -r requirements.txt
