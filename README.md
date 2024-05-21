# Brain Tumor Classification

This project uses deep learning techniques to classify brain tumors using MRI images.

## Dataset

The dataset contains MRI images of brain tumors. Images are classified into two categories: with tumor and without tumor. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri).

## Model Architecture

The model is a convolutional neural network (CNN) with the following layers:
- 3 convolutional layers
- 3 max pooling layers
- 1 fully connected layer
- 1 dropout layer
- 1 output layer

## Training Process

The model is trained using the Adam optimizer and binary cross-entropy loss. The training and validation data are augmented using image data generators.

## Evaluation Results

The model achieved an accuracy of XX% on the test set.

## Installation and Usage

1. Clone the repository:
   
Bash


    git clone https://github.com/your-username/brain-tumor-classification.git
    cd brain-tumor-classification
    
2. Install the required dependencies:
   
Bash


    pip install -r requirements.txt
    
3. Run the Jupyter Notebook:
   
Bash


    jupyter notebook notebooks/Brain_Tumor_Classification.ipynb
    
## Results Visualization

The training and validation loss and accuracy are visualized below:
![Training and Validation Loss](images/loss.png)
![Training and Validation Accuracy](images/accuracy.png)
