  # 🧠 GenAI Vanilla GAN Implementation

This repository contains an implementation of a **Vanilla Generative Adversarial Network (GAN)** built using deep learning frameworks. The goal of this project is to understand and demonstrate how GANs generate synthetic data by learning from real data distributions.

---

## 🚀 Brief Overview

Generative Adversarial Networks (GANs) consist of two neural networks:

- **Generator (G)** → Generates fake data from random noise  
- **Discriminator (D)** → Distinguishes between real and fake data  

These two models are trained together in a **minimax game**, where:

- Generator tries to fool the discriminator  
- Discriminator tries to correctly classify real vs fake  

---


---

## ⚙️ Features

- Vanilla GAN implementation from scratch
- Neural network-based Generator & Discriminator
- Training loop with adversarial loss
- Visualization of generated samples
- Loss tracking for both networks

---

## 🛠️ Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib

---

## 📊 How It Works

1. Random noise is sampled from a latent space
2. Generator converts noise → fake data
3. Discriminator evaluates real vs fake
4. Loss is computed:
   - Generator loss → how well it fools D
   - Discriminator loss → how well it detects fake
5. Backpropagation updates both networks

---

## 🧪 Training Process

- Input: Random noise vector
- Output: Generated samples (e.g., images)
- Optimization:
  - Binary Cross Entropy Loss
  - Alternating updates between G and D

---

## Results
  - Generator gradually learns to produce realistic samples
  - Discriminator improves in distinguishing real vs fake
  - Training stabilizes after multiple epochs

