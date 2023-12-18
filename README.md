# Leaf Doctors - Computer Vision Project

## Project Description

Welcome to Leaf Doctors, a computer vision project developed as the final assignment for COMSC 341-CV (Computer Vision) course. The goal of Leaf Doctors is to assist users in determining the health status of a leaf captured through images. The project achieves this by employing Sobel edge detection for image enhancement, leaf segmentation for isolating the leaf from the background, and a machine learning model for health classification.

## Team Information

- **Team Name:** ClimateTeam
- **Group Members:**
  - Julia Diep Ho
  - Sulagna Saha
  - Autumn Nguyen

## Project Components

### 1. Sobel Edge Detection

The Sobel edge detection code used in this project is inspired from the COMSC-341CV Fall 2023 course by Professor Melody Su.

### 2. Leaf Segmentation

For leaf segmentation, the project uses preliminery concepts from the Digital Epidemiology Lab's plantvillage_deeplearning_paper_analysis repository.

Reference: [plantvillage_deeplearning_paper_analysis](https://github.com/digitalepidemiologylab/plantvillage_deeplearning_paper_analysis)

### 3. Machine Learning Model Training (Path-specific❗️)

The code we uses to pre-process data and train the Machine Learning (ML) model is included in the Final Project Code notebook. However, we load the data from Google Drive, so **a few paths in the code are specific to our own Drive**. To be able to run this code on Google Colab, you will need to have the dataset on your Drive, mount your Drive to the Colab notebook, and change the paths to load the data from your Drive. This model is a Convolutional Neural Network that can do a binary classification to predict if the leaf is healthy or unhealthy.

### 4. Machine Learning Model Loading (Path-specific❗️)

We save the trained ML model in our Drive, so that we can quickly load it to do prediction without having do train a model again every time. We couldn't upload the model, even as a compressed zip file, onto Github due to Github's large file size limit, so we have made the model available publicly on [this Google Drive location](https://drive.google.com/file/d/1EA0234xTWX_lVsGccazf4XDBrQg8NDmv/view?usp=share_link).

### 5. GUI Code

After running the project, the GUI code allows users to capture an image of a leaf using their webcam. The captured image is then processed through Sobel edge detection and leaf segmentation before being classified by the loaded machine learning model.

<img width="1199" alt="Screenshot 2023-12-17 at 9 54 40 PM" src="https://github.com/MHC-FA23-CS341CV/computer-vision-final-project-climateteam/assets/93749279/220e1041-594b-4920-bda0-c8370ecd5078">
<img width="668" alt="Screen Shot 2023-12-11 at 8 38 46 AM" src="https://github.com/MHC-FA23-CS341CV/computer-vision-final-project-climateteam/assets/92401509/5a87c32f-a377-45c9-9417-849b1c8f716f">


## Data Used

The project utilizes data from the following source:

- **Data Source:** [Mendeley - Leaf Image Dataset](https://data.mendeley.com/datasets/t6j2h22jpx/1) (ver. 111223)


