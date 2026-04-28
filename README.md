# Baby Cry Analyser

An ML-powered classifier that detects the reason behind infant cries — 
hunger, pain, discomfort, and more — using audio signal processing.

Built in 24 hours at **Tensor V2.0 Hackathon, Udhgam 2.0** 
(Woxsen University, Feb 2026) by Team TRACELESS.

## Problem
Parents — especially first-time parents — struggle to understand why 
their baby is crying. This tool provides instant, data-driven insight.

## How it works
1. Audio files are loaded and processed using **Librosa**
2. Features (MFCCs, spectral data) are extracted from the audio
3. A trained ML classifier predicts the cry category

## Tech Stack
- Python · Librosa · Pandas · NumPy · Scikit-learn
- Dataset: [Baby Cry Sense Dataset](https://www.kaggle.com/) (Kaggle)

## Results
- Trained and compared multiple ML models
- Selected best-performing classifier based on accuracy

## Team
Built by Team TRACELESS at Woxsen University
