# NeuralNetworksHomeAssignment4

Student Information

- Name: Ruthvik Reddy Gaddam
- Student ID: 700755809 RXG58090
- Course: CS5720 Neural Networks CRN-23848

## Overview

This repository contains the final submission of the home assignment 5 of the Neural Networks course.

- File Structure:
- The assignment contains 4 tasks which were implemented separately in 4 python notebooks
    - HA5.pdf
    - ha5task3.ipynb
    - ha5task4.ipynb

## How to execute locally

Download the repository and install the mentioned packages in the requirements.txt file and run the cells of the Jupyter Notebook

## 1. Explain the adversarial process in GAN training. What are the goals of the generator and discriminator, and how do they improve through competition? Diagram of the GAN architecture showing the data flow and objectives of each component.


## 2. Choose one of the following real-world AI harms discussed in Chapter 12:
- Representational harm 
- Allocational harm 
- Misinformation in generative AI 

Describe a real or hypothetical application where this harm may occur. Then, suggest two harm mitigation strategies that could reduce its impact based on the lecture. 

## 3. Programming Task (Basic GAN Implementation) 
Implement a simple GAN using PyTorch or TensorFlow to generate handwritten 
digits from the MNIST dataset. 
Requirements: 
- Generator and Discriminator architecture 
- Training loop with alternating updates 
- Show sample images at Epoch 0, 50, and 100 
Deliverables: 
- Generated image samples 
- Screenshot or plots comparing losses of generator and discriminator over 
time 

#### Result

Printed the generated image samples at epochs 0, 50, 100. plots of losses of generator and discriminator have been plotted.

## 4. Programming Task (Data Poisoning Simulation) 
Simulate a data poisoning attack on a sentiment classifier. 
Start with a basic classifier trained on a small dataset (e.g., movie reviews). Then, 
poison some training data by flipping labels for phrases about a specific entity 
(e.g., "UC Berkeley"). 
Deliverables: 
- Graphs showing accuracy and confusion matrix before and after poisoning 
- How the poisoning affected results 

#### Result

Accuracy and confusion matrix for normal and poisoned model have been printed. 

## 5. Legal and Ethical Implications of GenAI 

Discuss the legal and ethical concerns of AI-generated content based on the 
examples of: 
- Memorizing private data (e.g., names in GPT-2) 
- Generating copyrighted material (e.g., Harry Potter text) 

Do you believe generative AI models should be restricted from certain data during training? Justify your answer. 

## 6. Bias & Fairness Tools 

Visit Aequitas Bias Audit Tool. 

Choose a bias metric (e.g., false negative rate parity) and describe: 
- What the metric measures 
- Why it's important 
- How a model might fail this metric 
Optional: Try applying the tool to any small dataset or use demo data.