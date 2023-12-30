# Pet Breed Identification with TensorFlow and ResNet-50

## Overview

This project involves the development of a model to identify pet breeds in the Oxford-IIIT Pet Dataset using TensorFlow. The dataset consists of 37 different pet breeds, and the task is to predict the breed category given an input pet image.

### Dataset

- Dataset: [Oxford-IIIT Pet Dataset](https://www.tensorflow.org/datasets/catalog/oxford_iiit_pet)
- Number of Classes: 37
- Number of Images per Class: Approximately 200

## Tasks

### (a) k-NN Classification with ResNet-50 Embeddings

1. Utilize the ResNet-50 model implemented in the TensorFlow library.
2. Perform k-NN classification with the embeddings produced by the pretrained ResNet-50.

### (b) Linear Classification with Pre-trained Embeddings

1. Use the pre-trained ResNet-50 embeddings for linear classification (multi-class logistic regression).
(Note: This is equivalent to training only the last fully-connected layer of a classification network with the feature extractor frozen).

### (c) Fine-tuning Image Classification Network

1. Fine-tune an image classification network end-to-end, changing the pre-trained weights as well.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pet-breed-identification.git
