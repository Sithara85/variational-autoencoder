# variational-autoencoder

In this notebook, a Variational Autoencoder (VAE) is created and used to generate synthetic data of the minority class of a credit loan dataset. A classification network is then trained based on both the original and synthetic data, and the performance is evaluated, using the AUC. Two benchmark models are implemented to assess the performance of the VAE. The notebook consists of three parts:

1. The necessary packages are loaded, and the dataset is imported and preprocessed.
2. Two benchmark models are implemented: Classification without any balancing and classification using synthetic data generated with the popular SMOTE technique.
3. The VAE is created and trained to then generate synthetic data. Based on this data, the classification network is trained and evaluated. 

Indeed, the VAE is able to outperform both benchmark models.

A more detailed description of the implemented experiments can be found here:

https://humboldt-wi.github.io/blog/research/information_systems_1819/generativemodels/
