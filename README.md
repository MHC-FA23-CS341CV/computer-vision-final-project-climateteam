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

### 3. Machine Learning Model Training (Note: Do not run this code)

The machine learning model training code is included in the project. However, it is advised not to run this code as the model has already been trained.

### 4. Machine Learning Model Loading

Load the pre-trained machine learning model using the provided code. This model is responsible for determining the health status of the captured leaf.

### 5. GUI Code

After running the project, the GUI code allows users to capture an image of a leaf using their webcam. The captured image is then processed through Sobel edge detection and leaf segmentation before being classified by the loaded machine learning model.
<img width="1486" alt="Screenshot 2023-12-17 at 12 27 28 PM" src="https://github.com/MHC-FA23-CS341CV/computer-vision-final-project-climateteam/assets/93749279/7d9e561e-571a-4d70-8990-03795996fe89">

## Data Used

The project utilizes data from the following source:

- **Data Source:** [Mendeley - Leaf Image Dataset](https://data.mendeley.com/datasets/t6j2h22jpx/1) (ver. 111223)


