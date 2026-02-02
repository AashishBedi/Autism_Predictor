# Autism Predictor

This repository contains a machine learning project designed to predict the likelihood of Autism Spectrum Disorder (ASD) based on behavioral and demographic data. By leveraging classification algorithms, this tool aims to provide an accessible and efficient preliminary screening mechanism.

## Overview

Autism Spectrum Disorder is a neurodevelopmental condition characterized by challenges with social interaction, communication, and restricted or repetitive behaviors. Early detection is crucial for timely intervention. This project utilizes datasets (such as those found on UCI Machine Learning Repository or Kaggle) to train models that can identify traits associated with ASD across different age groups.

## Features

* **Data Preprocessing:** Handles missing values, encodes categorical features, and performs feature scaling.
* **Multiple Classifiers:** Implementation and comparison of various algorithms such as Logistic Regression, Random Forest, and Support Vector Machines (SVM).
* **Performance Metrics:** Evaluates models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.
* **Predictive Analysis:** A script to input custom data points and receive a prediction.

## Tech Stack

* **Language:** Python
* **Libraries:** * `Pandas` & `NumPy` (Data Manipulation)
* `Scikit-learn` (Machine Learning)
* `Matplotlib` & `Seaborn` (Data Visualization)



## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/AashishBedi/Autism_Predictor.git
cd Autism_Predictor

```


2. **Install dependencies:**
```bash
pip install -r requirements.txt

```



## Usage

1. **Run the analysis:**
Execute the main notebook or script to see the data exploration and model training process.
```bash
python main.py

```


2. **Make Predictions:**
Follow the prompts within the script to input specific behavioral traits and obtain a result.

## Results

The models developed in this project have achieved significant accuracy in identifying ASD traits. For detailed performance reports, please refer to the `results/` folder or the visualizations within the Jupyter Notebook.

## Disclaimer

This tool is intended for **informational and educational purposes only**. It is not a medical diagnostic tool. If you have concerns about Autism Spectrum Disorder, please consult a qualified healthcare professional or specialist.

---

**Developed by Aashish Bedi**
