# Text-to-Image Generation using CGAN & Transformers

## Project Overview
This project implements a **comprehensive text-to-image generation pipeline** by integrating multiple AI components:

- Dataset analysis
- Text preprocessing
- Text embedding using Transformers
- Conditional GAN (CGAN) for image generation

The system simulates a **real-world AI workflow** where text descriptions are converted into meaningful visual outputs.

## Project Tasks Covered

### 1. Dataset Analysis
- Loaded and explored datasets (e.g., Oxford Flowers / CIFAR)
- Analyzed:
  - Number of classes
  - Image resolution
  - Data distribution
- Visualized images with labels/captions

---

### 2. Text Preprocessing & Embedding
- Used **Hugging Face Transformers**
- Steps:
  - Tokenization
  - Encoding
  - Embedding generation (CLIP/Text Encoder)
- Converted text → numerical vectors

---

### 3. CGAN Implementation
- Built **Conditional GAN**
- Generator input:
  - Noise vector
  - Label / text embedding
- Discriminator:
  - Validates image + condition pair

✔ Generated images for:
- Circle
- Square
- Simple patterns

---

### 4. Text-to-Image Pipeline (Final Integration)
