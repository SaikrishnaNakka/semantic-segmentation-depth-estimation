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

## 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/semantic-segmentation-depth-estimation.git
cd semantic-segmentation-depth-estimation

## Install dependencies
pip install -r requirements.txt

---
## ▶️ Run the Script
python image_segmentation_with_depth_estimation.py

## 🖼️ Sample Image
Ensure the vehicles.jpg file is present in the project root folder. You can also replace it with any other image of your choice.
## 💡 How It Works
-Loads the image using PIL
-Uses a pre-trained DPT model to predict depth
-Converts the depth output into a color-mapped image
-Visualizes and optionally saves the result
## 🧪 Requirements
Python 3.7+
PyTorch
Transformers (Hugging Face)
OpenCV
Pillow
Pandas
Matplotlib

## 📌 Output
- Saves the predicted depth map as depth_map_output.jpg.
- Displays input and output images side-by-side using matplotlib.

## 📚 License
This project is licensed under the [MIT License](LICENSE).
