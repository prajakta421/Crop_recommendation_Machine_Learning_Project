# Crop_recommendation_Machine_Learning_Project

  ## Project Overview :

This project is a Crop Recommendation System built using Machine Learning.
It predicts the most suitable crop to grow based on environmental and soil conditions such as:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH value

Rainfall

The model helps farmers make data-driven decisions to improve productivity.


##  Technologies Used :

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

## Project Structure:

Crop-Recommendation-Project/
│
├── crop.ipynb          # Jupyter Notebook (Model building)
├── model.pkl           # Saved trained model file
├── dataset.csv         # Dataset used for training
├── README.md           # Project documentation
└── requirements.txt    # Required libraries



 ## Machine Learning Model:

The following algorithm was used:

Random Forest Classifier

## Project Workflow :

Data Collection

Data Preprocessing

Label Encoding (if required)

Train-Test Split

Model Training

Model Evaluation

Model Saving using pickle

Prediction

## How to Save the Model (PKL File)
import pickle

# Save model
pickle.dump(model, open("rf_model_crop.pkl", "wb"))

# Load model
model = pickle.load(open("rf_model_crop.pkl", "rb"))



## How to Run the Project

Clone the repository

git clone https://github.com/prajakta421/Crop_recommendation_Machine_Learning_Project.git


Install required libraries

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook


Run crop.ipynb


## Model Accuracy:

Accuracy: 1.0 % 
