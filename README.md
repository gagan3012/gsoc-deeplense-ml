# GSOC 21 DEEPLENSE Project

## Task 1

### Simulating Superfluid Dark Matter (DM) with PyAutoLens

PyAutoLens is open source software for the analysis and modeling of strong gravitational lenses. Its target audience is anyone with an interest in strong gravitational lensing, whether that be study the mass structure properties of the foreground lens galaxy or the magnified properties of the backgrounds source.

**Task**: Modify and/or use the already existing functionality of PyAutoLens to simulate strong lensing from superfluid dark matter. Specifically, you will need to simulate the effects of lensing from a linear mass density - imagine this being a string of mass on galactic scales.

# Solution can be found [**here**](https://github.com/gagan3012/gsoc-deeplense-ml/blob/master/Test_I_Simulating_Superfluid_Dark_Matter_(DM)_with_PyAutoLens.ipynb)

## Task 2

### Specific Test II. Learning the DM representation 
### Unsupervised Anomaly Detection and Transfer Learning

The following link contains the network architecture and weights of an Adversarial Autoencoder trained on a large dataset of strong gravitational lensing images without substructure.

Link:
https://github.com/ML4SCI/ML4SCI_GSoC/tree/main/DeepLense/Domain%20Adaptation

**Task** : Use the provided model weights for weight initialization or feature extraction, and train an unsupervised deep learning algorithm of your choice to learn the distribution of the provided strong lensing images with no substructure to solve the task of unsupervised anomaly detection using PyTorch. Pick the most appropriate approach and discuss your strategy.						
Dataset: https://github.com/ML4SCI/ML4SCI_GSoC/blob/main/DeepLense/Domain%20Adaptation/lenses.tgz
Dataset Description: A set of simulated strong gravitational lensing images with and without substructure. 
Evaluation Metrics: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 

### Metrics Results: 

![image](https://user-images.githubusercontent.com/49101362/112737616-d8b65500-8f6c-11eb-8300-2e0d0d27339f.png)

### ROC Curve

![image](https://user-images.githubusercontent.com/49101362/112737663-216e0e00-8f6d-11eb-9e37-3eaa859e2c17.png)


#### AUROC = 0.6


# Solution can be found [**here**](https://github.com/gagan3012/gsoc-deeplense-ml/blob/master/Test_II_Learning_the_DM_representation.ipynb)



