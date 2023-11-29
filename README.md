 # Malaria Detection Using Deep Learning

## Introduction

This project focuses on the detection of malaria using deep learning techniques. It utilizes a smaller version of the malaria dataset, divided into two categories: train and test. The dataset consists of microscopic images of blood smears, categorized into two classes - Parasite and Uninfected.

## Dataset Context

The dataset is split into training and testing sets:

### Training Set:

- **Parasite:** 220 Images
- **Uninfected:** 196 Images

### Testing Set:

- **Parasite:** 91 Images
- **Uninfected:** 43 Images

You can use this dataset to build a Convolutional Neural Network (CNN) model for predicting whether a given blood smear image contains malaria parasites or is uninfected.

## CNN Model

![image](https://github.com/MadanBabu1314114/Malaria-Detection-Using-Deep-learning/assets/123216438/9b97f5f9-5e38-4da0-a54f-f95bc755a580)


The Convolutional Neural Network (CNN) employed in this project is designed to extract features from microscopic images to effectively classify them as Parasite or Uninfected. The architecture includes multiple convolutional layers for feature extraction, pooling layers for spatial reduction, and fully connected layers for classification.

## Project Structure

- **data:**
  - **train:**
    - **Parasite:** Folder containing training images of infected blood smears.
    - **Uninfected:** Folder containing training images of uninfected blood smears.
  - **test:**
    - **Parasite:** Folder containing testing images of infected blood smears.
    - **Uninfected:** Folder containing testing images of uninfected blood smears.

- **notebooks:** Jupyter notebooks for data exploration, model training, and evaluation. Note: These notebooks are designed to be run in Google Colab.

 

- **results:**

  ![image](https://github.com/MadanBabu1314114/Malaria-Detection-Using-Deep-learning/assets/123216438/08e66929-9a8e-483a-be14-6069730c832e)

  Visualizations and results obtained from the analysis.

- **accuracy**

  ![image](https://github.com/MadanBabu1314114/Malaria-Detection-Using-Deep-learning/assets/123216438/79cd2f4f-40ff-4a28-a9dd-c9c21f47684f)
 

  
  

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/MadanBabu1314114/Malaria-Detection-Using-Deep-learning.git
 
