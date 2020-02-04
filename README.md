# Malaria Parasite Detection in Thin Blood Smear Images by Retraining Pretrained Convolutional Neural Networks (VGG19)
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

```
Domain 		: Computer Vision, Machine Learning
Sub-Domain	: Deep Learning, Image Recognition
Techniques	: Deep Convolutional Neural Network, Transfer Learning, VGG19
Application	: Image Classification, Medical Imaging, Bio-Medical Imaging
```


## Description
* Detection of malarial parasites from thin Blood Smear images. Images were collected from Malaria screening research activity by National Institutes of Health (NIH). 
* Employed VGG19 Deep Learning (Convolutional Neural Network) and fine-tuned the model weights in the entire network to distinguish infected from uninfected images. Used Tensorflow 2.0 for model training. Incrementally unfroze and tuned all layers in the network.
* Image augmentation and resizing of images were done on the fly during the training process.
* Attained a loss (categorical crossentropy) 0.159 and an accuracy 95.7% on the test data.

## Dataset Details
Dataset Name		        : Malaria Cell Images Dataset
Original Dataset	        : [Malaria Datasets - National Institutes of Health (NIH)](https://lhncbc.nlm.nih.gov/publication/pub9932)
Number of Classes		    : 2

## Tools/ Libraries
```
Languages	    : Python
Tools/IDE	    : Jupyter. Notebook
Libraries	    : TensorFlow 2.0, VGG19
```

## Performance Metrics
| Dataset | Training | Validation |
| ------- | -------- | ---------- |
| Accuracy | 0.9206	| 0.9503 |
| Loss | 0.14285 | 0.1762 |
| Precision | 0.96 |
| Recall | 0.96 |
| ROC-AUC |		

## Model and Training Parameters
| Parameter | Value |
| --------- | ----- |
| Base Model |VGG19	| 
| Optimizer | Stochastic Gradient Descent |
| Loss Function | Categorical Crossentropy |
| Learning Rate | 0.0001 |
| Batch Size | 32 |
| Number of Epochs | Round #1 & #2: 10 epochs, Round#3: 35 epochs |	
 


