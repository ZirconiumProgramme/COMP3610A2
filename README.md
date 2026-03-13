NYC Yellow Taxi Tip Prediction - COMP 3610 Assignment 2
Author: Ryan Bramble

Course: COMP 3610: Big Data Analytics, Semester II (2025-2026) 

Overview
This project focuses on building, evaluating, and interpreting machine learning models to predict taxi trip tip amounts using the NYC Yellow Taxi Trip dataset. The analysis includes extensive feature engineering, data preprocessing, and the training of both traditional machine learning models and a deep learning neural network.
+1

The project addresses two primary tasks:

Regression: Predicting the exact tip_amount for a given taxi trip.

Classification: Predicting whether a trip will yield a high tip (defined as tip_amount > 20% of fare_amount).

Project Structure
assignment2.ipynb: The core analytical Jupyter Notebook containing the full pipeline for Part 1 (Data Preprocessing), Part 2 (Model Training), and Part 3 (Model Evaluation & Interpretation).

requirements.txt: A list of all Python dependencies and their specific version numbers required to run the notebook.

README.md: Project documentation and setup instructions.

.gitignore: Configuration file ensuring that large dataset files and local model artifacts are excluded from version control.

Setup Instructions
To replicate this environment and run the notebook locally, follow these steps:

Clone the repository:

Bash
git clone <your-repository-url>
cd <repository-folder>
Create and activate a virtual environment:

Bash
# On macOS/Linux
python3 -m venv .venv
source .venv/bin/activate

# On Windows
python -m venv .venv
.venv\Scripts\activate
Install the required dependencies:

Bash
pip install -r requirements.txt
Launch the Jupyter Notebook:

Bash
jupyter notebook assignment2.ipynb
Data Note
Due to file size constraints and version control best practices, the dataset (Transformed_TripData.parquet) is not included in this repository. To run this notebook, you must place the cleaned NYC Yellow Taxi dataset generated from Assignment 1 into the root directory of this project. The dataset is filtered to strictly include credit card transactions (payment_type = 1), yielding approximately 2 million rows.
+3

Models Evaluated
Regression Baselines: Linear Regression, Random Forest Regressor 

Classification Baselines: Logistic Regression, Random Forest Classifier 

Deep Learning: PyTorch Feedforward Neural Network

AI Disclosure:

AI was used to fully generate the Readme file
Assist with debugging 
Assist with styling
Assist with the summary function for Part 1 
AI was also used to gain learn about alternative ways to complete task such as to_dummies function
The Tools used was ChatGPT, GPT-OSS(20b), qwem-instruct(12b), Gemini(Thinking/Pro)
Everything else was understood and written by me

