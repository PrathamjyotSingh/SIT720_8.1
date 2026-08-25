# Sydney Housing Price Prediction and Decision Support System

## SIT720 – 8.1 Distinction Task

This project develops a machine learning-based housing price prediction and decision support system for selected Sydney suburbs. The project follows the complete machine learning workflow, including data collection, preprocessing, exploratory data analysis, feature engineering, regression modelling, model evaluation, prediction error analysis, comparison with human and Large Language Model (LLM) estimates, and deployment of a web-based prediction application.

## Project Objective

The primary objective is to predict the sale price of residential properties using property characteristics and suburb information. The project also investigates how machine learning predictions compare with human judgement and LLM-based estimates.

The final model is deployed through a simple web application that allows users to enter property information and obtain an estimated sale price.

## Repository Contents

| File                                    | Description                                                                                                                                   |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| `Sydney_Housing_Price_Prediction.ipynb` | Complete Jupyter notebook containing data preparation, exploratory analysis, feature engineering, model development, evaluation, and analysis |
| `sydney_housing_dataset.csv`            | Collected Sydney housing property dataset used for the project                                                                                |
| `app.py`                                | Web application for entering property information and generating predicted sale prices                                                        |
| `housing_price_model.pkl`               | Saved trained machine learning model used by the application                                                                                  |
| `requirements.txt`                      | Python dependencies required to reproduce the analysis and run the application                                                                |

## Machine Learning Workflow

The project covers the following stages:

1. **Problem Definition and Data Collection**

   * Selection of three Sydney suburbs representing different housing markets
   * Collection of sold-property information
   * Identification of relevant property characteristics
   * Discussion of data quality, missing information, bias, and limitations

2. **Data Understanding and Feature Engineering**

   * Exploratory data analysis
   * Housing price distributions
   * Comparison between suburbs
   * Analysis of trends and potential outliers
   * Identification of important predictors
   * Feature engineering

3. **Model Development and Evaluation**

   * Development of three regression models
   * K-fold cross-validation
   * Evaluation using appropriate regression metrics
   * Analysis of model complexity, underfitting, and overfitting
   * Selection of the most appropriate final model

4. **Prediction Failure Investigation**

   * Identification of the five properties with the largest prediction errors
   * Investigation of potential reasons for prediction failures
   * Discussion of limitations and unavailable information

5. **Human Judgement, Machine Learning, and LLM Comparison**

   * Selection of ten held-out test properties
   * Comparison of machine learning predictions, LLM estimates, and human estimates
   * Comparison against actual sale prices

6. **Deployment**

   * Development of a web-based prediction application
   * Integration of the trained machine learning model
   * User input and predicted sale price output

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Streamlit
* Joblib

## Running the Project

### 1. Clone the repository

```bash
git clone https://github.com/PrathamjyotSingh/SIT720_8.1.git
cd SIT720_8.1
```

### 2. Install dependencies

Create a Python environment if required, then install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open the Jupyter notebook:

```bash
jupyter notebook
```

Run the notebook from start to finish to reproduce the data analysis, feature engineering, model training, evaluation, and experimental results.

### 4. Run the web application

Start the application using:

```bash
streamlit run app.py
```

The application will open in a web browser. Users can enter the required property characteristics and receive a predicted sale price.

## Reproducibility

The repository contains the dataset, complete notebook, trained model, application source code, and dependency information required to reproduce the project and run the prediction application.

The notebook should be executed from beginning to end to reproduce the reported experimental results.

## Academic Integrity and GenAI Acknowledgement

Generative AI tools were used during the development of this project for planning, brainstorming, troubleshooting, and reviewing technical or written material where appropriate. All generated suggestions were critically evaluated, tested, and adapted by the student. The final analysis, modelling decisions, interpretation of results, and submitted work represent the student's own understanding and work.

## Author

**Prathamjyot Singh**

SIT720 – Machine Learning
Deakin University
