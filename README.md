# ACTION 2025 - Indonesian Food Classification

[![Competition](https://img.shields.io/badge/Competition-ACTION-blue)](https://github.com)
[![University](https://img.shields.io/badge/University-Surabaya%20University-green)](#)

## Project Description

This repository contains our submission for the **Data Mining ACTION 2025** organized by Surabaya University (UNESA). The competition challenges participants to develop accurate classification models for Indonesian food classification using computer vision techniques. Participants utilize semi-supervised learning approaches, advanced neural architectures, and data augmentation methods to achieve high classification accuracy.

## Problem Statement

This project aims to develop a model that can accurately classify Indonesian food from images. Using semi-supervised learning with a lightweight MLP architecture and SigLIP Vision Transformer for feature extraction, we achieve 96% accuracy. The implementation leverages:

- Self-training with pseudo-labeling for unlabeled data
- SE-Attention mechanisms for feature enhancement
- Advanced Test-Time Augmentation (TTA)
- Class weighting to handle imbalanced datasets
- Residual Feed-Forward Networks for training stability

The solution addresses challenges in food classification where labeled data is limited, making it valuable for:

- Automated food recognition systems
- Culinary heritage preservation and documentation
- Restaurant menu digitization
- Nutritional tracking applications

## Competition Overview

- **Event**: Data Mining ACTION 2025
- **Organizer**: Surabaya University (UNESA)
- **Category**: Data Mining - Computer Vision
- **Focus**: Indonesian food image classification
- **Objective**: Develop accurate models to classify Indonesian food dishes from images using semi-supervised learning techniques

## Dataset Information

This dataset contains images of various Indonesian food dishes for multi-class classification across 15 classes. The dataset presents a semi-supervised learning challenge where all images are initially unlabeled.

**Dataset Characteristics:**
- **Total Classes**: 15 Indonesian food categories
- **Training Data**: Unlabeled images requiring semi-supervised learning approach
- **Test Data**: Unlabeled images for final classification
- **Image Format**: Various food dish photographs
- **Challenge**: No pre-labeled training data provided

Due to the unlabeled nature of the dataset, we employed semi-supervised learning techniques including self-training, pseudo-labeling, and confidence-based sample selection to achieve classification accuracy.

## Results

**Competition Performance**
- **Public Leaderboard**: Top 2 | Accuracy: 0.96472
- **Private Leaderboard**: Top 9 | Accuracy: 0.95465
- **Preliminary Results**: Top 5

## Team Members

- Solo Bening Nuansa Nanditya
- Wildan Abid Al Hanif
- Aqila Khansa Hartanto

## Acknowledgments

- Surabaya University (UNESA) for organizing the ACTION 2025 event
- Competition organizers and mentors

---

*This repository is part of our participation in the Data Mining ACTION 2025 at Surabaya University.*