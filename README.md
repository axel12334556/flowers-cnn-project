# Flower classification – CNN & Transfer Learning

Deep Learning project (team of 3).

We classify photos of flowers into 5 classes (daisy, dandelion, roses, sunflowers, tulips) using the
[TensorFlow Flowers dataset](https://www.tensorflow.org/datasets/catalog/tf_flowers) (3,670 images).

## What's inside

`flowers_cnn_transfer_learning.ipynb` :

1. Dataset exploration and a stratified train / val / test split (70 / 15 / 15)
2. Baseline CNN trained from scratch
3. Improved CNN : data augmentation, batch normalization, global average pooling, dropout
4. Transfer learning with MobileNetV2 (ImageNet) : feature extraction then fine-tuning
5. Extra : comparison with EfficientNetB0
6. Error analysis (classification report, confusion matrix, misclassified images)
7. Grad-CAM visualisation

## How to run

The easiest way is Google Colab with a GPU (Runtime > Change runtime type > GPU).
The dataset and the pretrained weights are downloaded automatically.

Locally :

```
pip install -r requirements.txt
jupyter notebook flowers_cnn_transfer_learning.ipynb
```
