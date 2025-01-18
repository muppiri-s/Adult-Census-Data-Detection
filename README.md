# AWS SageMaker Project

## Overview
This project demonstrates the use of **AWS SageMaker** to build, train, and deploy machine learning models at scale. The primary objective is to utilize the Adult Census dataset to predict income levels using machine learning techniques.

## Dataset
- **Adult Census Dataset**
  - URL: [Adult Dataset on UCI Repository](https://archive.ics.uci.edu/dataset/2/adult)
  - The dataset is used to classify individuals based on their income levels.

## Tools and Technologies
- **AWS SageMaker**: For managing the end-to-end machine learning workflow.
- **S3**: For storing datasets and model artifacts.
- **XGBoost**: A powerful gradient-boosted decision tree algorithm used for training.
- **Debugging and Profiling Tools**: For performance monitoring and optimization during model training.

## Visualizations
After uploading the dataset to S3:
![Dataset Upload Screenshot](https://github.com/user-attachments/assets/dc0e2550-0150-42b5-a7a1-ffad4db07327)

## Notes
- This project leverages AWS SageMaker's capabilities to handle large-scale machine learning workflows.
- The XGBoost algorithm is utilized for its efficiency and scalability.
- Ensure proper IAM permissions are in place to facilitate seamless integration between SageMaker and other AWS services.
