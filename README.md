# Vehicle Classifier with Fastai

This repository contains a notebook showcasing a vehicle classifier using Fastai, capable of classifying seven types of vehicles: 'motorcycle', 'scooter', 'bicycle', 'truck', 'train', 'car', and 'bus'.

## Description

The project demonstrates the capabilities of the Fastai library in creating state-of-the-art deep learning models for various tasks. It employs techniques such as data augmentation and data cleaning to enhance the model's performance.

## Features

- **Data Collection**: The project utilizes the `jmd_imagescraper` library, which leverages the DuckDuckGo search API to scrape images for different vehicle types.
  
- **Data Preprocessing**: Images are organized into a dataset using Fastai's `DataBlock` API. Augmentations are applied to diversify the dataset.
  
- **Model Training**: Transfer learning is employed with a pre-trained ResNet18 model. The model is fine-tuned on the dataset to classify the different vehicle types.
  
- **Model Evaluation**: The notebook evaluates the model's performance using error rate metrics and confusion matrix analysis.
  
- **Model Deployment**: The trained model is exported for deployment. Inference is demonstrated on sample images using the deployed model.

## Usage

1. Run the notebook to collect, preprocess, train, evaluate, and deploy the vehicle classifier model.
2. Follow the instructions provided in the notebook to interact with the classifier and test it on sample images.

## Hugging Face Interface

You can also try out the vehicle classifier model using the Hugging Face interface. Click [here](https://huggingface.co/spaces/i4mbrems/vehicle_classifier) to access the interface.

## Installation

To run the notebook, ensure you have Fastai and jmd_imagescraper installed:

```bash
pip install -Uqq fastai
pip install -q jmd_imagescraper
