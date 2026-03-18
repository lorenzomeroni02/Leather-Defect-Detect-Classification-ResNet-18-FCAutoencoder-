# Leather-Defect-Detect-Classification-ResNet-18-FCAutoencoder-

### Deep Learning for Aritificial Intelligence - Università Cattolica del Sacro Cuore

👥 Team

* Matteo Gerevini
* Lorenzo Meroni

### Goal

The following project addresses the challenge of automated surface defect classification in leather manufacturing by comparing two fundamentally opposed Deep Learning paradigms.

* **Supervised Approach:** A fully supervised **Custom ResNet-18**, optimized to directly extract discriminative features from labeled data.
* **Hybrid Pipeline:** An innovative approach utilizing a **Fully Convolutional Autoencoder**. The model first undergoes unsupervised pre-training to capture complex leather morphology through spatial reconstruction. The resulting latent space is then specialized for classification via **Transfer Learning** and precise end-to-end **Fine-Tuning**.

This comparative analysis aims to evaluate the trade-offs between a native classifier and the discriminative potential of a reconstructive, unsupervised feature space.

### Dataset

We worked using this dataset available on Kaggle, which contains 3600 images of categories of leather defects

* https://www.kaggle.com/datasets/praveen2084/leather-defect-classification

