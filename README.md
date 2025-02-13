# Monet-Style GAN Project

## Overview
This project implements a Generative Adversarial Network (GAN) to transform photographs into Monet-style paintings. It was created as part of the Kaggle "I'm Something of a Painter Myself" competition.

## Project Structure
- `notebooks/monet_gan.ipynb`: Main project notebook containing model development and training
- `data/`: Directory containing training data
 - `monet_jpg/`: 300 Monet paintings (256x256)
 - `photo_jpg/`: 7,038 photographs (256x256)
- `generated_images/`: Directory containing generated Monet-style images
- `images.zip`: Submission file containing generated images

## Results
- Training completed in 5 epochs (for time and simplicity)
- Final Generator Loss: 1.0369
- Final Discriminator Loss: 1.0955
- Kaggle Public MiFID Score: 184.59

## Requirements
- TensorFlow 2.x
- Numpy
- Pillow
- Matplotlib
- tqdm

## Usage
1. Clone the repository
2. Install required packages
3. Run the notebook `monet_gan.ipynb`
4. Generated images will be saved in `generated_images/` directory