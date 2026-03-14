APS360 Project -- Waste Classification -- 

Waste Classification for Residential ApartmentsThis project develops an automated waste classification system using a Convolutional Neural Network (CNN). 

The goal is to distinguish between three main streams: Recyclables, Organics, and Garbage.

Dataset and Data ProcessingThe project uses the Garbage Classification dataset from Kaggle. 

After manual cleaning, 14,570 images were retained.Recyclables: 12,888 images Organics: 985 images Garbage: 697 images 

Model ArchitectureBaseline Model: A shallow Multi-Layer Perceptron (MLP) with 38,568,707 parameters.
Primary Model: A 5-block CNN with 1,702,659 parameters.

Results Baseline Test Accuracy: 89.15% Primary CNN Test Accuracy: 95.15%

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DwQH7gpNhyndRHKVaGxC9fyDRytK74cB?usp=sharing)
