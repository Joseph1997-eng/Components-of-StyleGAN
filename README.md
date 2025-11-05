# 🧠 Components of StyleGAN

A hands-on exploration of **StyleGAN (Style-Based Generator Architecture for Generative Adversarial Networks)** using PyTorch and Jupyter Notebook.  
This project breaks down the inner workings of StyleGAN — including its **mapping network**, **AdaIN (Adaptive Instance Normalization)**, and **style mixing** process — to help you understand how GANs generate high-quality, controllable images.

---

## 🚀 Quick Launch in Google Colab

You can run the notebook directly in Google Colab using the badge below 👇

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joseph1997-eng/Components-of-StyleGAN/blob/main/C2W3_Assignment.ipynb)

---

## 🧩 Project Overview

This repository contains an in-depth breakdown of the **StyleGAN architecture**, originally introduced by NVIDIA, focusing on:

- The structure of the **mapping network**
- Understanding **AdaIN (Adaptive Instance Normalization)**
- Exploring **style mixing** and **truncation trick**
- Visualizing **latent space interpolation**
- Learning how the generator and discriminator collaborate to improve image quality

---

## ⚙️ Setup Instructions

### 🔹 Option 1 — Run on Google Colab (Recommended)
Just click the “Open in Colab” badge above.  
No installation required — Colab provides GPU access automatically.

### 🔹 Option 2 — Run Locally
If you prefer to run on your local machine:

```bash
# Clone the repository
git clone https://github.com/Joseph1997-eng/Components-of-StyleGAN.git
cd Components-of-StyleGAN

# Install dependencies
pip install torch torchvision matplotlib numpy
