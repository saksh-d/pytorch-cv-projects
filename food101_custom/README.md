# Custom Food Image Classifier (Pizza, Steak, Sushi)

This project demonstrates how to work with a custom image dataset using PyTorch. A 3-class subset of the Food101 dataset is used to train a CNN classifier from scratch.

## Dataset

- Source: Subset from [Food101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/)
- 3 classes: Pizza, Steak, Sushi
- 100 images per class
- Pre-split into train and test folders
- Loaded using `torchvision.datasets.ImageFolder`

## Model

- Custom CNN designed for small-scale classification
- Convolutional layers followed by fully connected layers
- Trained using CrossEntropyLoss and Adam optimizer

## Results

- Achieved ~XX% test accuracy (fill in your result)
- Learned to distinguish among the three food types effectively

## References
 - https://github.com/mrdbourke/pytorch-deep-learning/
 - https://learnpytorch.io/

## How to Run

```bash
# Inside the food101_custom/ folder
jupyter notebook custom_dataset_food101.ipynb
