# Brain Tumor Classification

This repository contains code for classifying brain tumors using deep learning models.

## Requirements
- TensorFlow >= 2.0
- Python 3.x
- Other dependencies listed in `requirements.txt`

## Dataset
The dataset used for training is from Kaggle: [Brain Tumors 256x256 Dataset](https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256/data).

To use this dataset, download it from Kaggle and place the data in the `Data/` folder.

## Files
- `model_architecture.json`: JSON file containing the architecture of the model.
- `model_weights.h5`: H5 file containing the trained model weights.
- `train.py`: Script to train the model.

## How to run
1. Install the required dependencies using `pip install -r requirements.txt`.
2. Download the dataset from Kaggle and place it in the `Data/` folder.
3. Run the training script: `python train.py`.
