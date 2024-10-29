# Amazon Rainforest Image Classification with CNN

This project uses a Convolutional Neural Network (CNN) for multiclass classification on satellite images of the Amazon rainforest. Each image can have multiple tags corresponding to various land types and features.

## Project Overview
- **Dataset**: Satellite images from the [Kaggle Amazon Rainforest dataset](https://www.kaggle.com/competitions/planet-understanding-the-amazon-from-space/data).
- **Data Handling**: Images were downloaded, stored in Google Drive, and processed in Google Colab to handle the dataset size.
- **Model**: A CNN model with multiple convolutional and pooling layers, trained on varying subsets of the data to optimize accuracy.

## Notebooks
- **Data Extraction**: Downloads and extracts images from Kaggle.
- **Model Training**: Two versions; one using 30% of the training set and another using 10%. The larger subset achieves higher validation accuracy.

## Getting Started
1. Download dataset files from Kaggle.
2. Upload files to Google Drive.
3. Run the extraction notebook in Colab.
4. Train the CNN using one of the provided notebooks.

## Future Improvements
Optimize model architecture for better performance in classifying rainforest images.
