[Project Proposal](https://docs.google.com/document/d/1pwuYGbVma8OiFHTI-iN2m2P2oGrjt1MlXhvuB7ECuI0/edit?tab=t.0)


# Representational Geometry and Dynamics in Artificial Neural Networks of Visual Working Memory 

## Project Description
This project explores how different artificial neural architectures encode, maintain, and retrieve visual information. We analyze the geometry and dynamics of the representations across models, focusing on their implications for performance, robustness, and biological plausibility in visual working memory tasks.

We want to examine the following questions:
 1. How do spiking neural networks (SNNs) compare to traditional convolutional neural networks (CNNs) in encoding visual information for working memory tasks
 2. How do different memory architectures (RNN and SNN) handle maintenance and retrieval of encoded visual information in delayed match-to-sample tasks?
 3. How does the performance of an RNN and an SNN degrade as a function of increasing noise (delay) added during either the encoding or the maintenance phase of the task? Which architecture exhibits more robust representations?


## Used Dataset
We used MNIST and N-MNIST (Orchard et al., 2015) to examine our questions. Specifically:
   MNIST: Used for the standard Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN) benchmarks.
   N-MNIST: Used for the Spiking Neural Network (SNN) to leverage temporal spike-based data.

## Model Architecture
The project compares three distinct classes of architectures:

1. Convolutional Neural Network (CNN): * Structure: 5 Convolutional layers followed by 3 Fully Connected layers.
Focus: High-accuracy static feedforward encoding (Achieved 99.22% accuracy).

2. Spiking Neural Network (SNN): * Structure: Hidden layer of 1,000 Leaky Integrate-and-Fire (LIF) neurons.
Dynamics: Processed over 25 time steps to simulate biological spike-timing-dependent encoding.

3. Recurrent Neural Networks (RNN/LSTM/GRU): * Task: Delayed Match-to-Sample.
Focus: Analyzing fixed-point dynamics and the effect of distractors on information maintenance during the delay period.
<img width="845" height="418" alt="image" src="https://github.com/user-attachments/assets/06a3f4a3-a1b2-45ca-a3de-8c72f1779466" />

## Key Analytical Methods
Representational Dissimilarity Analysis (RDA): Using RDMs to visualize the geometric structure of neural representations.

Dynamical Similarity Analysis (DSA): Comparing the temporal trajectories of SNNs and RNNs.

## Requirements
To run the analysis and models, you will need:

Python 3.8+
PyTorch / Tonic (for N-MNIST handling)
NumPy & SciPy
Matplotlib & Seaborn (for RDM visualization)
Scikit-learn (for MDS and dimensionality reduction)




## Contributors 
- [Bogeng Song](https://github.com/bogeng-song)
- [Pranati Modumudi](https://github.com/pranmod01)
- [Willow Han](https://github.com/hwhan14)
- [Qingqing Yang](https://github.com/Qingqing-Yang-17)
- [Richard Tobing](https://github.com/Koogleblitz)
- [Liz Jaramillo](https://github.com/lizaneth)
- [Adrian Velez](https://github.com/anselmo0v)
- [Cherishma Kumar Subhasa](https://github.com/CherishSu)
- [Ananna Biswas](https://github.com/Anannabiswas)
- [Albin Spuler](https://github.com/ATSpuler)
- [Mostafa Miandari Hossein](https://github.com/Miandari)


## License 





