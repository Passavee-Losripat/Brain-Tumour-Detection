# Brain-Tumour-Detection

## About The Project
This project is a development of Convolutional Neural Network (CNN) model for detecting brain tumour in brain MRI images. The dataset is retrieved from [kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data) uploaded by Navoneel Chakrabarty.

After training for 15 epochs, the model acheive the accuracy of 0.9961 as shown in the figure belows.
![Accuracy Graph of Brain Tumour Detection](https://drive.google.com/file/d/1RKYKUrAlcxcwv7itqA94-EbomcpmDUvc/view?usp=sharing)

## Get Started
To run this repository locally, you should first create **Kaggle API Token** before uploading it into Google Colab. You may need to edit path of the downloaded dataset in cell 3, unzipping the dataset, cell 5, loading dataset, and cell 13, trying to predict the result from dataset. All of the dependencies used in training model are automatically downloaded in the beginning.

## Usage
This code provide basic training of CNN for detecting brain tumour from brain MRI images. The model can be downloaded and improved by applying data augmentation technnique, class-imbalanced improvement technique and finetuing model for better performance.

## What I have learned from this project
This is my first project about CNN in 2021 for educational purpose. I have learned basic usage of TensorFlow, Keras, and fundamentals of CNN during this projects. This inspires me to further study machine learning, especially in medical application
