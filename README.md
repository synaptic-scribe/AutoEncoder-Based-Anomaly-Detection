# Autoencoder-Based Image Segmentation on Hazelnut Dataset

## Project Overview
This project implements an autoencoder neural network for **image segmentation** to detect anomalies in hazelnuts using the **MVTec AD dataset**. The goal is to reconstruct normal (non-defective) hazelnuts and identify differences when the model fails to reconstruct defective ones.

## Dataset
- Dataset: [MVTec AD - Hazelnut Category](https://www.mvtec.com/company/research/datasets/mvtec-ad)

## How It Works
The autoencoder consists of:
- **Encoder**: Extracts features via Conv2D + MaxPooling.
- **Latent Space**: Compressed representation of the input.
- **Decoder**: Reconstructs the image using UpSampling + Conv2D.
- **Loss Function**: Binary Cross-Entropy.
- **Goal**: Reconstruct defect-free images; deviations in reconstruction suggest anomalies.

## Results 
<img width="1287" height="714" alt="e838b2de-60bc-42e6-9488-43a633903c7c" src="https://github.com/user-attachments/assets/5679fdef-3c30-4d42-bea2-7847b5556ed5" />


## Contributors
- [@synaptic-scribe](https://github.com/synaptic-scribe)
- [@heuristic-solver](https://github.com/heuristic-solver)
