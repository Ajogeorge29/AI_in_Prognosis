# AI_in_Prognosis
Repository Description
BONBID Preprocessing for 2024 Challenge

This repository contains Python scripts for preprocessing the data from the BONBID 2024 challenge, focusing on lesion segmentation and image normalization techniques for training machine learning models. The notebook automates the following tasks:

Loading and Normalizing MRI Images: Utilizes SimpleITK to read .mha files and normalize the ADC and Z-ADC maps.
Resampling: Resamples images to a consistent voxel size for uniformity in model training.
Data Cleaning and File Matching: Handles discrepancies in file naming between the ADC, Z_ADC, and Label directories, ensuring proper alignment for preprocessing.
Output: Saves the preprocessed images into a dedicated output directory for further use in model training.
This script is part of the BONBID 2024 challenge and is designed to process data for improved lesion segmentation and outcome prediction. It integrates SimpleITK for image processing and handles multi-modal data in preparation for machine learning workflows.

Features:

Automated preprocessing pipeline for ADC, Z-ADC, and label images.
Resampling for consistent voxel sizes.
Data normalization and alignment for model readiness.
Script prepared to handle large datasets with minimal input.
Requirements:

Python 3.x
SimpleITK
NumPy
To run the preprocessing script:

Clone the repository.
Download the BONBID challenge data (ADC, Z-ADC, and label files).
Run the notebook to preprocess and save the data.
