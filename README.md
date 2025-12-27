# Prompt-Conditioned Stable Diffusion Generator

A GPU-backed text-to-image generation system built using Stable Diffusion and Gradio.
This project focuses on inference engineering, prompt control, reproducibility, and
cost-efficient deployment on cloud GPU infrastructure.

---

## 🚀 Features

- Text-to-image generation using Stable Diffusion
- Style presets that modify prompt semantics (Realistic, Anime, Cyberpunk, Oil Painting)
- Manual control over inference steps and guidance scale
- Reproducible image generation using fixed random seeds
- Live interactive UI built with Gradio

---

## 🧠 Design Overview

- **Style Presets** abstract low-level diffusion behavior into high-level artistic controls
- **Inference Steps** control image quality vs latency trade-off
- **Guidance Scale** controls how strongly the model follows the prompt
- **Seed** ensures reproducibility for debugging and comparison

---

## 🔴 Live Demo (GPU-backed)

The live demo runs on a cloud GPU using Google Colab and Gradio.

⚠️ Note:
The public Gradio link is active while the Colab session is running and can be regenerated anytime.

👉 Run: `colab_demo.ipynb`

---

## 🛠️ Tech Stack

- Stable Diffusion (Diffusers)
- PyTorch
- Gradio
- Google Colab (GPU)

---

## 📁 Repository Structure


---

## 📌 Why No Model Training?

Training diffusion models is extremely resource-intensive.
This project focuses on inference-time engineering, parameter control,
and deployment — which are critical skills in real-world ML systems.
