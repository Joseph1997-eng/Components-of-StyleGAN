# 🧠 Components of StyleGAN

A practical implementation and exploration of the **StyleGAN architecture**, focusing on its key components — *Mapping Network, Adaptive Instance Normalization (AdaIN)*, and *Style Mixing*.  
This project demonstrates how StyleGAN learns to generate realistic images with control over visual attributes.

---

## 📘 Overview

StyleGAN (Style-Based Generator Architecture for Generative Adversarial Networks) is one of the most influential GAN architectures introduced by NVIDIA.  
This notebook explores:

- Mapping network (latent space transformation)
- Adaptive Instance Normalization (AdaIN)
- Style mixing and truncation trick
- Generator and discriminator structures
- Latent space interpolation and visualization

---

## ⚙️ Requirements

You can run the notebook locally or on **Google Colab**.  
If you’re using Colab, click the badge below to open and run it directly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joseph1997-eng/Components-of-StyleGAN/blob/main/your_notebook_name.ipynb)

*(Replace `your_notebook_name.ipynb` with your actual notebook filename.)*

### Local Setup

```bash
# Clone this repository
git clone https://github.com/Joseph1997-eng/Components-of-StyleGAN.git
cd Components-of-StyleGAN

# Install dependencies
pip install torch torchvision matplotlib numpy
