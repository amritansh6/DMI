# Assignment-2 : One Class Classification- Deep SVDD

Group Members :-

IIT2018142 Amritansh Mishra
IIT2018146 Shubham Kumar
IIT2018150 Aayush Talesara
IIT2018184 Ayush Verma
IIT2018185 Ayush Verma

## Introduction
Deep one-class classification for unsupervised Anomaly Detection.
Deep SVDD,jointly trains a deep neural network while optimizing a data-enclosing hypersphere in output space. Through this Deep SVDD extracts common factors of variation from data.

## Parameters
    num_epochs=100
    num_epochs_ae=100
    patience=50
    batch_size=200
    latent_dim=32


## Libraries Used
+ torch (0.4.1)
+ torchvision (0.2.1)
+ barbar (0.2.1)
+ numpy (1.19.5)
+ Pillow (8.1.2)
+ scikit-learn (0.24.1)


## Result

Inlier Class=1: 
Author Result: ROC AUC = 99.42
This Code: ROC AUC = 99.43


## Reference
[1] Deep One-Class Classification,ICML-2018, Lukas Ruff, Robert A. Vandermeulen, Nico Gornitz, Alexander Binder, Emmanuel Muller, Marius Kloft.
