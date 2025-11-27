This repository contains an end-to-end semantic segmentation pipeline for liver CT image segmentation using a U-Net convolutional neural network implemented in PyTorch. 
The project includes:

- Dataset loading + preprocessing

- Train/validation split

- Fully implemented U-Net model

- Dice + BCE combined loss

- Training loop with checkpoints

- Evaluation with mIoU and mPA

- Single-image inference + visualization

- Automatic output saving (predictions, loss curves, metrics)

Features:

Full training & evaluation pipeline:
Handles everything from loading data to saving the final metrics.

Clean U-Net implementation:
Includes encoder, bottleneck, decoder, skip connections, DoubleConv blocks, center cropping.

Medical segmentation metrics

- Dice Loss

- Mean IoU

- Pixel Accuracy (PA)

Automatic visualizations

- Predicted mask overlay

- Side-by-side comparison

- Loss curves saved as .png
