# Pix2Pix-GAN-Image-Translation
Deep Learning mini project using Pix2Pix GAN
# Image-to-Image Translation Using Pix2Pix GAN

## Project Overview
This Deep Learning mini-project uses a Pix2Pix Conditional Generative Adversarial Network (cGAN) to translate building facade layout maps into realistic building facade images.

## Technologies Used
- Python
- TensorFlow and Keras
- Google Colab
- Pix2Pix GAN
- U-Net Generator
- PatchGAN Discriminator

## Workflow
1. Load paired facade layout and real-image data.
2. Preprocess and resize the images.
3. Train the U-Net generator and PatchGAN discriminator.
4. Use adversarial and L1 loss functions.
5. Compare input layouts, target images, and generated outputs.

## How to Run
Open the `.ipynb` notebook in Google Colab and run its cells in order. Enable a GPU if available.

## Files
- `Image_to_Image_Translation_Pix2Pix_GAN.ipynb` — runnable notebook
- `Pix2Pix_GAN_Project_Code.py` — Python source code
- `Pix2Pix_GAN_Project_Code.pdf` — code listing for reference

## Note
Training time and output quality depend on the runtime, dataset availability, and number of epochs.
