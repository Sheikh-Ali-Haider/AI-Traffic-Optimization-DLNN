# AI-Driven Urban Traffic Optimization

**University of Management and Technology, Lahore**  
Deep Learning & Neural Networks (CS4152) — Spring 2025

## Overview
End-to-end deep learning pipeline for urban traffic optimization
using computer vision, time-series forecasting, anomaly detection,
NLP, and reinforcement learning.

## Pipeline
| Module | Technology | Purpose |
|--------|-----------|---------|
| Module 1 | YOLOv8 | Vehicle detection (50k frames, ~93% accuracy) |
| Module 2 | LSTM | Traffic flow forecasting |
| Module 3 | VAE | Anomaly detection (100/2000 windows) |
| Module 4 | BERT/KeyBERT | Social media event extraction |
| Module 5 | Q-Learning RL | Traffic signal control |
| Module 6 | Ethical Audit | Fairness & emission analysis |

## Results
- 50,000 frames processed
- ~93% detection accuracy
- 100 anomalies detected out of ~2,000 test windows
- ~30% estimated queue reduction under RL control

## Tech Stack
Python · YOLOv8 · TensorFlow/Keras · LSTM · VAE · 
KeyBERT · Q-Learning · BDD100K · Google Colab