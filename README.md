# DDoS Detector by Machine Learning

## Overview

Welcome to the DDoS Detector by Machine Learning repository! This project aims to leverage machine learning techniques to detect Distributed Denial of Service (DDoS) attacks in network data. The process involves initial data preprocessing using the `pre-processing.ipynb` file, followed by model application and evaluation using the `ML-model-applying.ipynb` file.

## Data Preprocessing

The `pre-processing.ipynb` codes serve as the initial step in our pipeline. It takes raw data with a shape of (225745, 79) as input and produces a refined CSV file with a shape of (225741, 67). Additional data extraction tasks have been performed, such as identifying the most frequently used ports and analyzing the distribution of attacks across these ports.

## Model Application

The heart of the project lies in the `ML-model-applying.ipynb` file, where machine learning models are applied and evaluated. The process involves the following steps:

1. **Cross-Validation:** The data is partitioned into subsets to facilitate robust model training and evaluation.

2. **Model Application Function:** A versatile function is employed for seamless application of machine learning models. This function handles the fitting of the model, prediction, metric gathering (accuracy rate, precision score, recall score, and F1 score), and the visualization of the confusion matrix.

## Example Output: RandomForest Model (n_estimators = 60)

An example output for the RandomForest model with 60 estimators is shown below:

![RandomForest Model Output](https://user-images.githubusercontent.com/123311716/215292461-9e3ffa2e-956e-4144-8783-4c4486ed2267.PNG)

## How to Use

Feel free to explore the notebooks in this repository to understand the details of the data preprocessing and model application. You can use these notebooks as a foundation for building your own DDoS detection system or as a reference for similar machine learning projects.

## Acknowledgments

Special thanks to the contributors and open-source community for their support and collaboration on this project.


## Get Started

To get started, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/fissid/DDoS_Detector_ML.git

2. Explore the pre-processing.ipynb and ML-model-applying.ipynb notebooks for detailed insights into the project.

3. Customize the code to fit your specific requirements and data.

4. Contribute and share your enhancements with the community!

Happy coding!

Feel free to adapt it further based on your specific project details and preferences!
