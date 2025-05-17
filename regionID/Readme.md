# Region Classification Model

This project implements a fine-tuning approach for region classification using the ConvNeXt Tiny architecture pre-trained on ImageNet. The model classifies images into 15 distinct regions.

## Key Features

- **Base Model**: ConvNeXt Tiny (state-of-the-art CNN architecture with transformer-like properties)
- **Training Strategy**: Transfer learning with fine-tuning
- **Preprocessing**: Image resizing to 256×256, data augmentation with random horizontal flips and color jitter
- **Regularization**: Dual regularization with dropout (0.3) and stochastic depth (0.3) to prevent overfitting
- **Learning Rate Schedule**: ReduceLROnPlateau scheduler for adaptive learning rate adjustment
- **Hyperparameter Optimization**: Systematic evaluation of learning rates, dropout rates, and stochastic depth probabilities
- **Model Selection**: Automatic tracking and saving of best-performing model checkpoints

The model achieves improved performance through the combination of modern CNN architecture and effective regularization techniques, evaluated through rigorous validation tracking and hyperparameter exploration.

## Links:-
https://drive.google.com/file/d/1Z2WblIJPAGopGTaHa4q4-5OlOOfuHHAA/view?usp=drive_link