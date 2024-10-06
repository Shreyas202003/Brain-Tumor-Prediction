# Brain Tumor Prediction using CNN

## Project Overview
This project aims to predict the presence of brain tumors using convolutional neural networks (CNNs) on MRI scans. The model leverages deep learning to classify MRI images into tumor and non-tumor categories with high accuracy.

## Key Features
- **Data Preprocessing**: Images are resized and normalized to improve model performance.
- **Model Architecture**: CNN with multiple layers to detect patterns in MRI images.
- **Training and Evaluation**: The model is trained on a labeled dataset of brain MRIs and evaluated using accuracy, precision, and recall metrics.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shreyas202003/Brain-Tumor-Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the training script:
   ```bash
   python train.py
   ```
2. Use the model for predictions on new images:
   ```bash
   python predict.py --image_path /path/to/image
   ```

## Dataset
The dataset contains MRI images of brains with and without tumors. It is preprocessed to have uniform image dimensions.

## Results
The model achieved an accuracy of **X%** on the test set. Future improvements could involve fine-tuning the model for better precision.

