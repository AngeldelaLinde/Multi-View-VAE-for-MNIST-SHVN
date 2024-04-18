# Multi-View VAE for MNIST-SHVN

This repository contains code for implementing a Multi-View Variational Autoencoder (VAE) for the MNIST-SHVN dataset. The VAE is capable of learning latent representations from both the MNIST and SVHN (Street View House Numbers) datasets and generating images from both domains.

## Introduction

Variational Autoencoders (VAEs) are generative models capable of learning latent representations of input data. Multi-View VAEs extend this concept to learn latent representations from multiple input domains simultaneously. In this project, as part of the Deep Learning subject in the Master of Machine Learning program, which I completed with two other classmates, we implement a Multi-View VAE for the MNIST and SVHN datasets, allowing the model to generate images from both domains.

## Getting Started

To run the code, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the required dependencies (PyTorch, NumPy, Matplotlib, Seaborn).
3. Run the provided Python scripts or notebooks.

## Datasets

The MNIST and SVHN datasets are used for training and testing the Multi-View VAE. These datasets contain images of handwritten digits (MNIST) and street view house numbers (SVHN).

## Usage

You can use the provided scripts and notebooks to train the Multi-View VAE on your own datasets or experiment with different hyperparameters and architectures. The `multi_view_vae.ipynb` notebook provides a step-by-step guide with detailed explanations.

## Results

The trained Multi-View VAE can generate realistic images from both the MNIST and SVHN domains. Additionally, it learns meaningful latent representations that capture the underlying structure of the data. Visualizations such as t-SNE plots are provided to demonstrate the effectiveness of the learned representations.

## References

- Kingma, D. P., & Welling, M. (2014). Auto-Encoding Variational Bayes. arXiv preprint arXiv:1312.6114.
- Doersch, C. (2016). Tutorial on Variational Autoencoders. arXiv preprint arXiv:1606.05908.
- Maaløe, L., Sønderby, S. K., Sønderby, C. K., & Winther, O. (2019). BIVA: A Very Deep Hierarchy of Latent Variables for Generative Modeling. arXiv preprint arXiv:1902.02102.

## Authors

- Ángel de la Linde Valdés
- María Ordieres Álvarez
- Alexia Durán Vizcaíno

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
