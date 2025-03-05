# Data606 Project 2

## Overview
This project is part of the **Data606** course and involves analyzing a dataset of medical images using deep learning techniques. The dataset is sourced from Kaggle, and various preprocessing, visualization, and modeling techniques are applied.

## Dataset
- **Source**: Kaggle ([CXR8 Selected Dataset](https://www.kaggle.com/datasets/myylee/cxr8-selected))
- **Description**: A dataset containing chest X-ray images used for classification and analysis.

## Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

### 2. Installing the Dependencies 
pip install kaggle seaborn matplotlib opencv-python tensorflow numpy pandas

### 3. Downloading the dataset
import os
os.environ['KAGGLE_CONFIG_DIR'] = "/content/"
!kaggle datasets download -d myylee/cxr8-selected --unzip

### 4. Project Structure

/your-repo-name
│── Data606_P2.ipynb   # Jupyter Notebook with the analysis
│── data/              # Directory to store dataset files
│── models/            # Trained models (if any)
│── images/            # Sample images used for visualization
│── README.md          # This file
