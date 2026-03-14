# Waste Classification for Residential Apartments

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DwQH7gpNhyndRHKVaGxC9fyDRytK74cB?usp=sharing)

**APS360 Project** 

---

## Overview

This project implements an **waste classification system** using a **Convolutional Neural Network (CNN)**. The goal is to help residents correctly sort waste into three streams:

| Stream       | Description                          |
|-------------|--------------------------------------|
| **Recyclables** | Paper, plastic, metal, glass, etc.   |
| **Organics**    | Food scraps, yard waste, compostables |
| **Garbage**     | Non-recyclable, non-organic waste    |

Correct sorting improves recycling rates and supports waste policies.

---

## Features

- **Three-way classification**: Recyclables, Organics, Garbage  
- **CNN-based model**: Image-based recognition for waste items  
- **Kaggle dataset**: Built on the [Garbage Classification](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification) dataset  
- **Colab**: Run training and inference in [Google Colab](https://colab.research.google.com/drive/1DwQH7gpNhyndRHKVaGxC9fyDRytK74cB?usp=sharing) with no local setup  

---

## Dataset & Data Processing

- **Source**: [Garbage Classification](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification) on Kaggle  
- **Content**: Images of waste items labeled by category  
- **Processing**: Standard augmentation and preprocessing for CNN training (resizing, normalization, train/validation split as implemented in the notebook)

## Model

- **Architecture**: Convolutional Neural Network (CNN) for image classification.  
- **Input**: Images of waste items.  
- **Output**: Class probabilities for Recyclables, Organics, and Garbage.  

Details on layers, hyperparameters, and training procedure are in the Colab notebook.


- **Dataset**: [Garbage Classification](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification) on Kaggle  
- **Course**: APS360 – Applied Fundamentals of Deep Learning  

---

## License

This project is for educational purposes (APS360). Dataset usage should follow the terms of the original Kaggle dataset.
