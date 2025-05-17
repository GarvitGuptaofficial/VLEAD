# TerrainAngleNet

A deep learning model for predicting terrain angle orientation from images using DINOv2 vision transformer backbone.

## Overview
TerrainAngleNet uses a fine-tuned DINOv2 ViT-B/14 transformer model to predict the angular orientation of terrain from satellite or aerial imagery. The model outputs a normalized 2D vector representing the terrain angle.

## Features
- Built on Facebook's DINOv2 pre-trained vision transformer
- Transfer learning with partial freezing of backbone layers
- Advanced data augmentation with RandAugment
- Stochastic depth for improved regularization
- Angular error calculation for terrain orientation prediction

## Usage
The model takes an RGB image as input and outputs a 2D normalized vector representing the terrain angle. Angular error is measured in degrees for model evaluation.

## Link to Best Saved Model
https://drive.google.com/file/d/1lm-jnPq3r71e7kHFO8JMM6vln6CZ2Zrc/view?usp=sharing


