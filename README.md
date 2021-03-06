## Deep-learning Radiomics techniques for classification modelling

### Introduction
This is the code for the paper entitled "Deep learning-based computer-aided diagnosis of individual lymph node metastatic status in esophageal squamous cell carcinoma using routine CT imaging"

This code includes feature extraction from handcrafted radiomics and pretrained Deep Convolutional Neural Network (CNN) model and then further model training and validation by machine learning approaches.

### Data

The size-based measurements including short-axis diameter and volume and deidentified clinical characteristics for all the individual lymph nodes have been uploaded.

### Methods
Analysis flowchart.
- Radiological features extracted from the deep learning method and handcrafted radiomics method
- Machine learning methods in model construction
- Model evaluation

### Requirement
All requirements are given in ```requirements.txt```
#### Python requirements
- numpy 1.16.3
- pandas 0.24.2
- scipy 1.2.1
- SimpleITK 1.2.0
- Keras 2.2.4
- scikit-learn 0.21.1

#### R requirements
- psych 1.8.12
- data.table 1.12.6


### Reference

[
Computational Radiomics System to Decode the Radiographic Phenotype
](https://doi.org/10.1158/0008-5472.CAN-17-0339)

[
Deep Residual Learning for Image Recognition
](https://arxiv.org/abs/1512.03385)







