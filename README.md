# Skin Cancer Classification using Deep Learning

This project focuses on the accurate classification of skin cancer images using deep learning techniques. By leveraging transfer learning and addressing data imbalance, the project aims to contribute to enhanced medical diagnostics in the field of dermatology.

## Objective

The main objective of this project is to develop a deep learning model that can accurately classify skin cancer images into different categories. The project aims to assist medical professionals in making more precise diagnoses by providing a reliable tool for identifying various types of skin cancer.

## Approach

1. **Data Exploration and Visualization:** The project starts with a thorough analysis of skin cancer image metadata using libraries such as Pandas, Seaborn, and Matplotlib. This exploration provides insights into class distribution, age, gender, and localization.

2. **Data Balancing:** Addressing class imbalance is a crucial step. Resampling techniques are employed to create a balanced dataset, allowing the model to learn effectively from all classes.

3. **Model Architecture:** Transfer learning is utilized with the pre-trained EfficientNetB7 model. The model architecture is customized by adding Global Average Pooling and a tailored output layer for multi-class classification.

4. **Training and Evaluation:** The model is trained using the balanced dataset and evaluated on validation data. Training progress is monitored through loss and accuracy metrics over epochs.

5. **Visualization:** The project includes visualizations such as training and validation curves, as well as a confusion matrix to assess the model's performance.

## Impact

- Enhanced Diagnostics: The project's deep learning model enhances the accuracy of skin cancer classification, offering valuable support to medical professionals in their diagnostic efforts.
- The model gained an accuracy of 92%

## How to Use

1. Clone this repository: `git clone https://github.com/yourusername/skin-cancer-classification.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python script to reproduce the project's workflow.
4. Explore the visualizations and model performance.

## Data Source

The HAM10000 dataset from Kaggle is used for this project. It contains skin cancer images along with corresponding metadata.

## Dependencies

- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Seaborn
- Matplotlib


