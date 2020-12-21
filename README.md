# Comparing the Performance of Stochastic Algorithms in Generating Adversarial Attacks on Image Classifiers

This project aims to compare the performance of three stochastic algorithms in generating adversarial attacks on image classifiers:
1. DeepSearch, from the paper *Deepsearch: A Simple And Effective Blackbox Attack For Deep Neural Networks* by F. Zhang, S. Chowdhury, and M. Christakis
2. POBA-GA, from the paper *POBA-GA: Perturbation Optimized Black-Box Adversarial Attacks Via Genetic Algorithm* by J. Chen, M. Su, S. Shen, H. Xiong, and H. Zheng
3. PSO, from the paper *Attacking Black-Box Image Classifiers With Particle Swarm Optimization* by Q. Zhang, K. Wang, W. Zhang and J. Hu

We originally collaborated using Google Drive and Google Colab. Feel free to check this link (https://drive.google.com/drive/folders/1zniHYkyOdiINbFyRr9wpVaCbK4UZ6rov?usp=sharing) to see our group's shared drive.

This repository contains the following files and directories:

**GA_results/** - some saved adversarial attack examples from POBA-GA trials on the same input image with different perturbations
**ckpts/** - the saved checkpoint file for POBA-GA (checkpoint is updated every generation in the algorithm)
**sample_images/** - sample images used for algorithm testing
**Batch_Test_GA.ipynb** - POBA-GA implementation
**Deep_Search_Final.ipynb** - DeepSearch implementation
**PSO.ipynb** - PSO implementation
