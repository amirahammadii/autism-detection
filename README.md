# autism-detection
1. Introduction
This repository implements a machine learning model to assist in diagnosing Autism Spectrum Disorder (ASD). The project involves data preprocessing, feature extraction, and deploying an LSTM-based diagnostic tool with a user-friendly interface.

2. Project Overview
The notebook integrates several tools to analyze behavioral data and predict autism severity. It leverages:

Deep Learning Models: LSTM-based architecture for sequential data.
Data Preprocessing: Text cleaning and feature scaling.
Web Interface with Widgets: User inputs behaviors for model predictions.
3. Dataset
The dataset captures children’s social, non-verbal, and behavioral patterns. Key attributes include:

Unique Behaviors: Describes behaviors prompting a diagnosis.
Social Deficits: Rates social interaction capabilities.
Non-verbal Communication: Measures abilities in non-verbal cues.
Relationships: Indicates if the child can maintain friendships.
Sensory Responses: Rates sensitivity to stimuli.
4. Model Architecture
The diagnostic tool uses LSTM layers to handle sequential input data. Key steps include:

Text Cleaning:
Removes non-alphanumeric characters and converts text to lowercase.
Model Building:
The model processes both text inputs and numerical features.
5. Installation
Clone the repository:
git clone https://github.com/your-repository/asd-diagnostic-tool.git  
cd asd-diagnostic-tool  
Install the required packages:

pip install -r requirements.txt  
Download the dataset and place it in the project directory.

6. Usage
Load the Notebook:
Open the notebook in Jupyter or Google Colab.

Run Data Preprocessing:
Prepare the data by cleaning text and scaling features and adjust as needed.

Train the Model:
Train the LSTM model.

Predict Autism Level:
Use the web interface to input behavior descriptions and receive predictions:

Interface Demo:
Interactive widgets allow users to input text and get instant predictions.
