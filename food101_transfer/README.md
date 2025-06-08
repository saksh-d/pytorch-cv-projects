# Transfer Learning with EfficientNet on Custom Food Dataset

This project applies transfer learning using EfficientNet-B0 (pretrained on ImageNet) to classify images of pizza, steak, and sushi from a small Food101 subset.

## Dataset

- Same 3-class subset from the previous project
- Images resized and normalized to match EfficientNet input requirements
- Loaded using custom `data_setup.py` utility

## Model

- Base: `torchvision.models.efficientnet_b0` with pretrained weights
- Final classifier layer modified to output 3 classes
- Only classification head trained (optional: unfreeze for fine-tuning)

## References
 - https://github.com/mrdbourke/pytorch-deep-learning/
 - https://learnpytorch.io/

## How to Run

```bash
# Inside the food101_transfer/ folder
jupyter notebook transfer_learning_food101.ipynb
