

# SOC_mrophix

[![Python](https://img.shields.io/badge/python-3.8+-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/streamlit-app-green)](https://streamlit.io/)
[![License](https://img.shields.io/badge/license-MIT-yellow)](LICENSE)

---

## 🚀 Overview

**SOC_mrophix** is a project focused on **Generative Adversarial Networks (GANs)** for image manipulation and enhancement.  
It combines **interactive web applications** using **Streamlit** with **Jupyter notebooks** for experimentation, enabling easy image generation, latent space exploration, and projection of real images into GAN latent space.

---

## 📁 Repository Structure

```
SOC_mrophix/
├── interfacegan/                 # Streamlit web application
│   └── app.py                    # Main Streamlit app
├── clip2stylegan_base.ipynb      # CLIP + StyleGAN integration notebook
├── clip2stylegan_base_my_approach.ipynb  # Custom approach to CLIP-StyleGAN
├── preojecting_image_on_gan.ipynb        # Projecting real images into GAN latent space
├── stylegan2_projecting_images_with_my_fork.ipynb # Author's fork for StyleGAN2 projection
├── latents_dataset.zip           # Precomputed latent vectors dataset
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation

```

---

## 🖥️ Streamlit Web Interface

The **`interfacegan/`** directory contains a **Streamlit application** that serves as the user-friendly interface for the project.  
The app allows you to:

- Upload images or input text prompts.
- Generate images using trained GAN models.
- Explore and visualize latent space manipulations.
- Adjust parameters to modify generated image outputs in real-time.

**Run the app locally:**

```bash
git clone https://github.com/Jeet1309/SOC_mrophix.git
cd SOC_mrophix/interfacegan
pip install -r ../requirements.txt
streamlit run app.py
```

---

## 🧪 Jupyter Notebooks

1. **`clip2stylegan_base.ipynb`**
   Integration of **CLIP with StyleGAN** to generate images from text descriptions.

2. **`clip2stylegan_base_my_approach.ipynb`**
   Custom approach by the author to enhance CLIP-StyleGAN integration.

3. **`preojecting_image_on_gan.ipynb`**
   Projects real images into GAN latent space to generate new images while preserving features.

4. **`stylegan2_projecting_images_with_my_fork.ipynb`**
   Author’s fork of **StyleGAN2** demonstrating projection with possible optimizations.

These notebooks are designed for learning, experimentation, and practical GAN applications.

---

## 🛠️ Installation

**Prerequisites:**

* Python >= 3.8
* Streamlit

**Install dependencies:**

```bash
pip install -r requirements.txt
```

---

## 💡 Usage

* Use the Streamlit app for interactive image generation.
* Use notebooks for custom experimentation, testing different GANs, and exploring latent spaces.

---

## 🌟 Features

* Text-to-image generation using CLIP + StyleGAN.
* Image projection into latent space for manipulation.
* Interactive web interface for easy experimentation.
* Custom approaches and optimizations by the author.

---

## 📚 References

* [StyleGAN](https://github.com/NVlabs/stylegan2)
* [CLIP](https://github.com/openai/CLIP)
* [Streamlit Documentation](https://docs.streamlit.io/)

---


