# **Generative Latent Diffusion Model for Hot-Dog Generation**

## **Overview**
This project implements a generative latent diffusion model (Denoising Diffusion Probabilistic Model - DDPM) to generate hot-dog images from pure noise. We leverage a pretrained Variational Autoencoder (VAE) from the Stable Diffusion 2 backbone to obtain latent embeddings, avoiding the high computational cost of training an encoder from scratch.

Inspired by the **hot-dog detector** from the TV show *Silicon Valley*, this coursework challenges us to create a hot-dog image generator using diffusion-based techniques. The generated images will be tested against a provided hot-dog detector to evaluate their plausibility.

## **Features**
- **Latent Diffusion Model (DDPM)**: Trains a diffusion model in the latent space of a pretrained VAE.
- **Pretrained VAE Encoder-Decoder**: Uses Stable Diffusion 2’s VAE to encode and decode images efficiently.
- **Unconditioned Generation**: Generates images purely from noise without additional text conditioning.
- **Hot-Dog Detector Evaluation**: Tests the quality of generated images with a provided detector.

## **Dataset**
We use a curated dataset of hot-dog images for training. The dataset consists of clean, well-labeled images that facilitate effective model training.
