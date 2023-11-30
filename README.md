# Network Traffic Anomaly Detection Using Dynamic Graph Embeddings

## Overview

This project aims to detect anomalies in network traffic using machine learning models and dynamic graph embeddings. It utilizes the KDD Cup 1999 dataset to train and evaluate various models, focusing on real-time anomaly detection capabilities. The core idea is to represent network traffic as dynamic graphs, embedding these graphs into continuous vector spaces, and apply machine learning algorithms for effective anomaly detection.

## Key Features

- **Data Preprocessing**: Includes cleaning, structuring, and preparing network traffic data.
- **Graph Embedding**: Converting network traffic data into graph structures for dynamic representations.
- **Machine Learning Models**: Utilizing algorithms like Random Forest, Gradient Boost, AdaBoost, and others for anomaly detection.
- **Hyperparameter Tuning**: Optimizing models for better accuracy and efficiency.
- **Evaluation**: Assessing models based on accuracy, F1 score, ROC/AUC curves, and more.

## How to Run the Project

1. **Clone the Repository**: Download or clone this repository to your local machine.
2. **Install Requirements**: Run `pip install -r requirements.txt` to install the necessary Python packages.
3. **Dataset Preparation**: Ensure the KDD Cup 1999 dataset is downloaded and placed in the specified directory.
4. **Run the Scripts**: Execute the Python scripts in the order mentioned in the project directory. Each script corresponds to different stages of the project, from data preprocessing to model evaluation.
5. **Model Training and Evaluation**: Follow the instructions within each script to train models and evaluate their performance.

## Achievements

- Achieved an accuracy exceeding 90% in detecting network anomalies.
- Demonstrated the effectiveness of dynamic graph embeddings in representing temporal network dynamics.
- Highlighted the advantages of dynamic graph embeddings over static techniques in network traffic analysis.
- Successfully implemented machine learning models, handling substantial data volumes and maintaining performance.

## Requirements

This project requires Python 3.x and several libraries listed in `requirements.txt`. Ensure all dependencies are installed to run the project smoothly.

## Conclusion

This project represents a significant step towards enhancing network security through advanced data science techniques. It showcases the potential of machine learning and dynamic graph embeddings in addressing the ever-evolving challenges in network traffic anomaly detection.
