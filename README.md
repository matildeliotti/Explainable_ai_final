# Explainable_ai_final for anomaly detection in credit card transactions

The dataset used for this code can be found here: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

This repository contains the code demonstration for my final assignment in Explainable AI (XAI). It explores the effectiveness of two XAI methodologies: SHAP and DiCE (Counterfactual Explanations) when applied to anonymized financial fraud data.

## Project Structure
`shap_in_nb.ipynb`: Jupyter Notebook containing the data preparation, Random Forest model training, and the complete SHAP evaluation (Waterfall plot).
`counter-ex.ipynb`: Jupyter Notebook containing the DiCE (Counterfactual Explanations) implementation.
`creditcard.csv`: The dataset required to run the models. (you should download it from the link provided above and place it in the same folder as the models' files)

## Installation Steps
To run these notebooks, you will need Python 3.8+ and Jupyter installed on your machine. 

1. Clone this repository to your local machine and enter the directory:
   ```bash
   git clone https://github.com/matildeliotti/Explainable_ai_final.git
   cd Explainable_ai_final
   ```

2. install the dependencies:
   ```bash
   pip install pandas scikit-learn shap dice-ml matplotlib
   ```

## Usage guide
1. Open your terminal or command prompt and paste:
   ```bash
   jupyter notebook
   ```

3. To evaluate SHAP, open `shap_in_nb.ipynb` file and run the cells.
   
4. To evaluate Counterfactuals, open `counter-ex.ipynb` file and run the cells.
