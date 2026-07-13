# SpectraSight AI

**Team:** Golden Bugs

## Overview

SpectraSight AI is an AI-powered web application developed for **Infrared Image Colorization and Enhancement for Improved Object Interpretation**.

Infrared satellite imagery plays a crucial role in remote sensing, particularly during nighttime and adverse weather conditions. However, these images are inherently monochrome, exhibit low contrast, and lack the visual details available in visible-spectrum imagery. This makes accurate interpretation of geographical features and objects significantly more challenging.

SpectraSight AI addresses this challenge by integrating image enhancement techniques with AI-driven infrared-to-RGB colorization. The platform improves image quality while preserving semantic integrity, enabling more accurate visualization and interpretation of satellite imagery.

---

## Problem Statement

Infrared satellite images often suffer from:

- Low contrast and poor visibility
- Lack of realistic color information
- Difficulty in identifying geographical features
- Reduced performance in downstream computer vision tasks

Our objective is to enhance infrared imagery and generate realistic RGB representations while preserving the structural and semantic characteristics of the original scene.

---

## Features

- Secure User Authentication
- Infrared Satellite Image Upload
- Super-Resolution Enhancement
- Image Sharpening
- Contrast Boost
- Image Denoising
- AI-based Infrared-to-RGB Colorization
- Land Cover Analysis
- Performance Evaluation
- Analytics Dashboard

---

## System Workflow

1. User uploads an infrared satellite image.
2. Enhancement parameters are configured.
3. The image undergoes preprocessing and enhancement.
4. The AI model performs infrared-to-RGB colorization.
5. Semantic refinement preserves important land-cover information.
6. The processed image is evaluated using image quality metrics.
7. Results and analytics are displayed to the user.

---

## Technology Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Python

### Image Processing
- OpenCV

### AI & Deep Learning
- Deep Learning Models
- Image-to-Image Translation

### Dataset
- Landsat 8/9 Satellite Imagery

---

## Evaluation Metrics

The generated outputs are evaluated using standard image quality metrics:

- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)
- FID (Fréchet Inception Distance)
- Inference Time

These metrics ensure that the enhanced images maintain structural consistency, visual realism, and computational efficiency.

---

## Applications

SpectraSight AI can be applied in:

- Disaster Management
- Remote Sensing
- Environmental Monitoring
- Urban Planning
- Land Cover Analysis
- Agricultural Monitoring
- Forest Monitoring
- Earth Observation

---

## Repository Structure

```
Spectra-ai/
│
├── frontend/
├── backend/
├── public/
├── src/
├── README.md
├── package.json
├── requirements.txt
└── assets/
```

---

## Demonstration

**Live Application:**  
(Add your deployed website link)

**Project Demonstration Video:**  
(Add your YouTube link)

**Presentation:**  
(Add your Google Drive PPT link)

---

## Project Information

**Project Name:** SpectraSight AI

**Team Name:** Golden Bugs

**Hackathon:** HackHazard 2026

---

## Future Scope

- Support for multiple satellite datasets
- Improved colorization using advanced generative AI models
- Real-time satellite image processing
- Integration with object detection and segmentation models
- Cloud-based deployment for scalable processing

---

## License

This project is developed for educational and hackathon purposes.

---

## Acknowledgement

We would like to thank the HackHazard organizing team for providing an opportunity to develop and showcase this solution. SpectraSight AI reflects our effort to apply Artificial Intelligence and Computer Vision to improve satellite image interpretation and contribute toward practical remote sensing applications.
