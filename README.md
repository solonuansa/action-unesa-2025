# ACTION 2025 - Indonesian Food Classification

[![Competition](https://img.shields.io/badge/Competition-ACTION-blue)](https://github.com)
[![University](https://img.shields.io/badge/University-Surabaya%20University-green)](#)

## Project Description

This repository contains our submission for the **ACTION 2025 Machine Learning Competition** organized by Surabaya University (UNESA). The competition challenges participants to develop accurate Machine Learning models for Indonesian food classification using computer vision techniques. Participants utilize semi-supervised learning approaches, advanced neural architectures, and data augmentation methods to achieve high classification accuracy.

## Problem Statement

This project aims to develop a machine learning model that can accurately classify Indonesian food from images. Using semi-supervised learning with a lightweight MLP architecture and SigLIP Vision Transformer for feature extraction, we achieve 93% accuracy. The implementation leverages:

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

- **Event**: ACTION 2025 Machine Learning Competition
- **Organizer**: Surabaya University (UNESA)
- **Category**: Machine Learning - Computer Vision
- **Focus**: Indonesian food image classification
- **Objective**: Develop accurate deep learning models to classify Indonesian food dishes from images using semi-supervised learning techniques

## Dataset Information

This dataset contains images of various Indonesian food dishes for multi-class classification.

- **Format**: Food image files (train and test sets)
- **Target Variable**: Indonesian food dish classification labels
- **Features**: Image pixel data and features extracted through SigLIP Vision Transformer
- **Approach**: Semi-supervised learning with labeled seed data and pseudo-labeling

## Results

**Competition Performance**
- **Public Leaderboard**: Top 2
- **Private Leaderboard**: Top 9
- **Model Accuracy**: 93%

## Team Members

- Wildan Abid Al Hanif
- Nugroho Ardiyanto
- Solo Bening Nuansa Nanditya

## Acknowledgments

- Surabaya University (UNESA) for organizing the ACTION 2025 event
- Competition organizers and mentors
- Dataset providers

---

*This repository is part of our participation in the SRIFOTON Machine Learning Competition 2025 at Sriwijaya University.*