# Deep Learning Signature Verification Project

This project implements a Siamese Neural Network for handwritten signature verification, utilizing three different datasets. The goal is to distinguish between genuine and forged signatures.

## Datasets Used

1. **Dataset 1**: A signature dataset for real vs forged signature classification.

   https://www.kaggle.com/datasets/shreelakshmigp/cedardataset
   
2. **Dataset 2**: Another signature dataset with real and forged signatures.

   https://www.kaggle.com/datasets/eryash15/re-arranged-data
   
3. **Dataset 3**: A collection with multiple datasets containing real and forged signatures.

   https://www.kaggle.com/datasets/divyanshrai/handwritten-signatures


## Features

- **Data Preprocessing**: Grayscale images are resized and normalized.
- **Siamese Network**: Utilizes a pair of CNNs to compare two images and predict if they belong to the same class (real or forged).
- **Model Evaluation**: Performance is evaluated using accuracy, precision, recall, and F1 score.
- **Pair Generation**: Generates pairs of images for training, validation, and testing, with labels indicating if they are from the same class.
- **Visualization**: Displays sample image pairs with their corresponding labels.

## Installation

```bash
pip install tensorflow opencv-python scikit-learn matplotlib
```
## How to Run
- **Clone the Repository**
- **Prepare the Datasets**
- **Run the Code**
