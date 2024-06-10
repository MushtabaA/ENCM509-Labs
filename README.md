# ENCM 509 - Fundamentals of Biometric Systems Design Labs

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

## Lab 1

Introduction to libraries such as NumPy, Matplotlib, and SciPy

## Lab 2

The purpose of this lab is to utilize statistical analysis to distinguish between "genuine" and "imposter" written signatures. Before applying statistical analysis, we will be collecting written signatures using the _Wacom Intuos_ tablet. We'll use this tablet to capture coordinate and pressure values at 200 points/sec as the pen moves across the tablet. The tablet is also capable of recognizing 1024 levels of pressure which will be especially useful in statistical analysis later on. In addition, we'll also utilize the software _SigGet_ to collect and convert the data to CSV files collected by the tablet. Throughout the lab we will utilize these CSV file samples to plot histograms, 2D and 3D colormaps, as well as normal distributions of both velocity and pressure and the calculation of both mean $(\mu)$ and standard deviation $(\sigma)$ in order to understand and compare trends in the distribution/dispersion of the data between both "genuine" and "imposter" written signatures to see how they differ.

## Lab 3

The purpose of this lab is to understand biometric-based verification between genuine and imposter signatures for 1:1 matching. In the previous lab, we utilized values such as pressure, time, and coordinates, however, in this lab, we will separate the data into 2 simple classes and train the data based on the EM algorithm. After training the data, we will also utilize the Gaussian Mixture Model (GMM) to calculate log-likelihood scores in order to distinguish the classes of genuine and imposter signatures, essentially "verifying" if the signature is genuine or not. In addition, we will also use the log-likelihood score to calculate both the mean $(\mu)$ and standard deviation $(\sigma)$ of both the imposter and genuine scores in order to plot normal distributions, illustrating how they vary with one another.

## Lab 4

In this lab we will be focusing on image pre-processing and feature extraction of fingerprints. We will be collecting fingerprints using the _Digital Persona UareU 4500_, and because the quality of data is affected by many factors, we will collect both good and bad quality fingerprints for analysis. Throughout the lab we will conduct a number of image processing techniques such as normalization and segmentation as well as pre-processing and de-noising techniques such as contrast enhancement (histogram equalization) and the Wiener filter. After applying these processing techniques, we will then calculate the number of Minutiae (ridge endings and bifurcations) and Singularities (points of cores, deltas) in order to assess their impact on the image details of the fingerprints.

## Lab 5

In this lab we will be focusing on image processing and fingerprint matching. We will be using fingerprints collected by using the _Digital Persona UareU 4500_. We will be focusing on two main matching algorithms, matching based on Minutiae count (ridge ending and bifurcation), and matching based on scores obtained by Gabor filtering. In addition, we will also change the parameters of Gabor filtering such as the angle and frequency in order to see if it has a visual impact on the processed fingerprint image. Lastly, after running both types of matching algorithms, we will also select thresholds in order to see their impact on the number of true positive matches and false negative matches.

## Lab 6

In this lab, we will explore facial recognition via Principal Component Analysis (PCA), using the AT&T Database of Faces. Employing Python and Jupyter Notebook, our focus will be on face detection, image processing, and classification through PCA feature extraction and Euclidean Distance matching. We will adjust PCA parameters to study their impact on facial representation and experiment with threshold settings to analyze their effects on true positive and false negative match rates. This practical approach aims to deepen our understanding of biometric verification within facial recognition, blending theoretical concepts with hands-on experience.

## Lab 7

In this lab, we will undertake the task of hand gesture recognition using data collected by the _Ultra Leap_ developed by _Leap Motion_. After the data is collected, we will be utilizing deep learning in order to regonize different hand gestures. More specifically, we will utilize a classifier, _Long Short-term Memory_ (LSTM) which is a deep learning model for time-series analysis. Throughout the lab, we will prepare our data, preprocess it, create our model, and performing classification while also changing specific parameters before classification such as the testing set size, number of LSTM layers, and the dropout probability in order to see their effects on accuracy, etc.

## Lab 8

In this lab, we explore Bayesian Networks (BNs) for machine reasoning using PyAgrum.
We'll construct BNs that mimic real scenarios, like the Diamond Princess infection outbreak.
The lab involves setting up network structures and conditional probability tables (CPTs).
We'll perform inference to understand how factors like age and gender influence susceptibility.
Exercises in Jupyter Notebook will guide us through these processes.
By manipulating BNs, insights into probabilistic decision-making will be gained.
We aim to show BNs as a robust framework for reasoning under uncertainty.
This practical approach will enhance our comprehension of BNs' applications.
Ultimately, we'll learn to make informed decisions based on probabilistic models.
