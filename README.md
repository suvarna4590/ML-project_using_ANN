### Human Cognitive Performance Prediction using ANN
#### Project Overview
This project uses an Artificial Neural Network (ANN) to predict human cognitive performance levels (Low, Medium, High) based on lifestyle and behavioral features such as sleep duration, stress level, screen time, caffeine intake, and more.
The goal is to build a machine learning model that can analyze human habits and estimate cognitive performance.
#### Dataset
The dataset contains information about human daily habits and cognitive scores.
**Features used:**
- Age
- Sleep Duration
- Stress Level
- Daily Screen Time
- Caffeine Intake
- Reaction Time
- Memory Test Score
- Gender
- Diet Type
- Exercise Frequency
**Target:**
- Cognitive Score Level:Low,Medium,High

The target is created by converting cognitive score into 3 categories using binning.
#### Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib (for visualization)
### Data Preprocessing
**Steps performed:**
- Removed duplicate values
- Dropped unnecessary columns
- Converted cognitive score into categories (Low/Medium/High)
- Encoded categorical variables
- Scaled numerical features
- Split dataset into training and testing sets
#### Model Architecture (ANN)
A Sequential Artificial Neural Network is used:
- Input layer
- Hidden Dense layers (ReLU activation)
- Output layer (Softmax activation for multi-class classification)
- Loss function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation metric: Accuracy
#### Model Training
The model is trained on training data and evaluated on test data.
Evaluation metrics:

Training accuracy

Testing accuracy
