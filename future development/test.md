# Machine Learning Project Documentation

## Repository: [ScanEat ML Deliverables](https://github.com/ScanEat-team/ml-deliverables)

### Overview
This repository contains the machine learning models and related assets for the ScanEat app. The models aim to:
- Predict Body Mass Index (BMI).
- Predict total nutritional intake value.
- Compare UPC-scanned products with daily intake recommendations for fat, sugar, or sodium.

#### 1. **Dataset Information**
- **Raw Data:** Original datasets used for training and testing the models.
	1. Dataset for BMI Model Training (consist of weight, height, and sex)
	2. Dataset for Total Daily Nutrition Prediction Training (consist of weight, height 
	   (get the predicted BMI from the previous model), age, sex, and adding base 
           information for nutritional intake from Permenkes No 28 Tahun 2019) 
	3. Dataset for UPC barcode [UPC Barcode](https://github.com/ScanEat-team/ml-deliverables/tree/main/current%20use%20model/dataset)
- **Processed Data:** Preprocessed datasets (e.g., normalized, cleaned, feature-engineered versions).

#### 2. **Code**
- **Data Preparation Scripts:**
  - Scripts for data cleaning, feature extraction, and transformation.
  - Code to derive user-specific features like age from birthdate.
- **Model Training:**
  - Jupyter notebooks or Python scripts for training each model.
  - Hyperparameter configurations.
- **Model Evaluation:**
  - Scripts for evaluating model performance (e.g., accuracy, precision, recall, RMSE).
- **Inference Pipelines:**
  - Code for making predictions or recommendations using the trained models.

#### 3. **Model Files**
- Trained model weights (.h5, .pkl, or similar formats).
- Model architecture definitions.
- Version control for models (e.g., changelog or version history).

#### 4. **Documentation**
- **Project Overview:** Objectives and scope.
- **User Guide:**
  - Instructions for setting up the environment.
  - Running scripts for training, evaluation, and inference.
- **Technical Details:**
  - Model architectures used:
    - Neural networks for BMI prediction and daily nutritional intake prediction.
  - Dataset preprocessing techniques.
  - Hyperparameters and tuning strategies.
- **Contributors:** Names and roles of project contributors.

#### 5. **Environment Setup**
- `requirements.txt` for Python dependencies.
- Environment configuration files (e.g., `.env` or `.yaml`).
- Dockerfile or containerization details (if applicable).

#### 6. **Testing**
- Unit tests for scripts and modules.
- Integration tests for end-to-end pipelines.
- Test datasets and expected outputs.

#### 7. **Results**
- Model performance metrics (e.g., confusion matrix, AUC-ROC curves).
- Visualization of results (e.g., charts, graphs).
- Comparative analysis with baseline models.


#### 9. **Future Directions**
- Planned features or improvements.
- Known issues and potential solutions.

---
### Additional Details from Notebook:
- **Model Implementation:**
  - Neural networks are used for BMI prediction and daily nutritional intake prediction.
  - Both models require installation of specific Python libraries, as outlined in the "Installation" section.
