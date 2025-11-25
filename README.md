# Elevatelabs-Task7
VM Classification – Task 7 (ElevateLabs)

This project implements Support Vector Machine (SVM) classification using the Pima Indians Diabetes Dataset.
The goal of this task is to perform data preprocessing, handle missing values, train an SVM model, evaluate its performance, and visualize the decision boundaries.

📌 Project Overview

This task includes:

Loading and cleaning the dataset

Handling missing values using mean imputation

Feature scaling with StandardScaler

Splitting data into training/testing sets

Training an SVM classifier

Evaluating results using:

Accuracy Score

Confusion Matrix

Classification Report

Plotting the SVM classification decision boundary

Final conclusion on model performance

📂 Dataset

The dataset used is the Pima Indians Diabetes Dataset, which contains medical diagnostic features and a target variable indicating diabetes presence (1) or absence (0).

⚙️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/yourrepo.git


Install required libraries:

pip install -r requirements.txt


Run the Python script:

python svm_task7.py

📊 Results

Dataset successfully preprocessed

Missing values handled using mean

SVM model trained using RBF kernel

Model scored:

Training accuracy: (Shown in output)

Test accuracy: (Shown in output)

Classification graph visualized for 2 selected features

📈 Visualization

The project includes:

SVM decision boundary plot

Scatter plot of positive vs negative diabetes cases

📁 Files in This Repository
File	Description
svm_task7.py	Main SVM model code
README.md	Documentation
svm_plot.png (optional)	Classification graph image
📝 Conclusion

This implementation demonstrates how SVM can be used for medical classification tasks, along with preprocessing, scaling, and visualization.
The model achieves good accuracy and clearly separates classes using nonlinear kernels.
