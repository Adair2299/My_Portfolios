# Personal Portfolio

This repository contains selected technical materials showcasing my work in **Machine Learning, Computer Vision, Deep Learning, and Robotics**.

> **For viewing only. Please do not distribute, reproduce, or reuse any materials without permission.**
> Copyright © Guanchen Liu. All rights reserved.

## Projects

## Mini GPT — From-Scratch Transformer Language Model

**PyTorch | Transformer | Self-Attention | NLP | Web Deployment**

**[View Source Code on GitHub](https://github.com/Adair2299/B5c_TinyLLM_3_MiniChatbot)**

A tiny GPT-style language model built from scratch using PyTorch, **without pretrained models or external AI APIs.** Trained on a constrained vocabulary and a small conversational dataset, the project demonstrates how a Transformer can learn to generate simple English responses with limited computational resources.

### Interactive Mini GPT

The trained model is deployed as an interactive chatbot website, allowing users to explore basic English conversations within its limited vocabulary.

**[The website of MiniGPT Chatbot](https://tiny-english-chatbot.onrender.com/)**

<img width="960" height="440" alt="Chatbot Demo 2 - good" src="https://github.com/user-attachments/assets/6dd5a990-d655-48b8-8326-b0a8fabc3987" />

### Model & Training Data

Built and trained a Transformer-based chatbot from scratch using PyTorch with GPU acceleration, leveraging a constrained vocabulary of 174 tokens and 18,536 question–answer pairs. The model demonstrates lightweight, low-cost language modeling without pretrained weights or external AI APIs.

<img width="1920" height="1080" alt="3237d78f-76cd-4157-8095-7b7c1d6bfc49" src="https://github.com/user-attachments/assets/997b0a19-0a6f-4fa4-bad3-4825b9dd952e" />

### Inside Transformer Training

To visualize how the model learns, I recorded and animated real model parameters and activations throughout training, including **Q/K/V projection matrices, token embeddings, causal attention maps, and training/validation loss**.

The visualization shows how the Transformer's internal representations evolve from random initialization through successive training epochs.

<img width="1080" height="611" alt="transformer_training_animation_v8_1080p1 (1)" src="https://github.com/user-attachments/assets/5e7038e8-5fd6-4077-a3b2-d118e97f6a4e" />

*An educational, small-scale language model demonstrating end-to-end model development, training, visualization, and deployment.*

---

## CloudJet — AI-Powered Steel Structure Climbing Inspection Robot

**Robotics | Computer Vision | Deep Learning | Embedded Systems**

[**CloudJet Robot Manual — English Version**](https://github.com/Adair2299/My_Portfolios/blob/main/CloudJet%20Robot%20Manual%20English%20Version.pdf)

CloudJet is a magnetic climbing robot designed for automated inspection of steel structures, including bridges, industrial facilities, and storage tanks. It integrates computer vision-based surface corrosion detection, piezoelectric sensing for internal damage assessment, and wireless remote monitoring.

<img width="240" height="240" alt="1b6d6dd06784156b4bea3190aa33fbad" src="https://github.com/user-attachments/assets/f413ce59-cca9-4af4-807d-69e7a361fca9" />


### Robot in Action

The robot climbs steel surfaces using magnetic wheels and supports remote operation through LAN-based control software.

<img width="240" height="240" alt="Cloudjet github demo (1)" src="https://github.com/user-attachments/assets/cd79daf7-49df-4601-a828-fd9e8e055cd8" />

### AI-Powered Damage Detection

A U-Net-based semantic segmentation model identifies surface corrosion and classifies it into three severity levels. Piezoelectric sensing enables quantitative assessment of internal structural damage.

<img width="240" height="240" alt="d1e0429dae760c2e399c4410afe46b24 en" src="https://github.com/user-attachments/assets/c9d75a19-0b97-48d6-87ef-0bc0d5fac812" />


### Key Specifications

| Feature | Performance |
|---|---|
| Surface damage resolution | ≤ 0.5 mm² |
| Internal damage resolution | ≤ 6.5 μm |
| Continuous operation | ≥ 4 hours |
| Minimum climbing surface diameter | 50 cm |

*Performance specifications are based on laboratory testing of an R&D prototype.*

---

### Deep Learning Model for Piezoelectric Sensor Signals

[**Deep Learning Model for Piezoelectric Sensor Signals.pdf**](https://github.com/Adair2299/My_Portfolios/blob/main/Deep%20Learning%20Model%20for%20Piezoelectric%20Sensor%20Signals.pdf)

A specialized **deep learning architecture for piezoelectric sensor signals**, designed around noise characteristics observed in real-world sensor operating environments.

The project incorporates an **attention mechanism** to improve the model's ability to focus on informative signal regions under noisy conditions.

The document includes:

* Model architecture and methodology
* Quantitative results on the test set
* Visualization of model performance
* Comparison of results **before and after introducing the attention mechanism**

---

### Point Cloud Vectorizer

[**Point Cloud Vectorizer Abstract and Demo.pdf**](https://github.com/Adair2299/My_Portfolios/blob/main/Point%20Cloud%20Vectorizer%20Abstract%20and%20Demo.pdf)

A project developed as part of **3D Building Reconstruction Based on Computer Vision and Large Language Models**.

I explored and developed a **point-cloud boundary vectorization and feature extraction tool** for converting geometric information from 3D point clouds into vectorized representations.

The document presents the project's concept, workflow, and demonstration results.

---

## Technical Focus

**Machine Learning · Deep Learning · Computer Vision · Point Clouds · Robotics · Sensor Signal Processing · Attention Mechanisms · Large Language Models · Structural Inspection**

---

**Author: Guanchen Liu**

UC Berkeley — MEng in Systems Engineering
