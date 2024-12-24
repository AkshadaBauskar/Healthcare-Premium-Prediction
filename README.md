# Healthcare Premium Prediction

## Project Overview
This project aims to build a predictive model for estimating healthcare insurance premiums based on demographic and medical factors such as age, BMI, smoking habits, and medical history. The predictions are made accessible through a cloud-deployed Streamlit application for insurance underwriters.

The model was developed as part of the project for Shield Insurance by AtliQ AI and achieves a high prediction accuracy to streamline insurance quote processes.

## Features
- Predict healthcare insurance premiums with high accuracy (>97%).
- Handle various data preprocessing tasks, including outlier treatment, feature engineering, and multicollinearity reduction.
- Provide an interactive Streamlit app for insurance underwriters to input customer details and view predictions.
- Deployed on a cloud platform for easy accessibility.

## Dataset
- The dataset includes labeled data on demographic and medical factors affecting healthcare premiums.
- Preprocessing steps include:
  - Handling missing values and duplicates.
  - Outlier treatment for age and income columns.
  - Feature encoding and scaling.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/AkshadaBauskar/Healthcare-Premium-Prediction.git
2. Navigate to the project directory:
   ```bash
   cd Healthcare-Premium-Prediction
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the Streamlit app:
   ```bash
   streamlit run app/artifacts/main.py

## Usage

### Jupyter Notebooks
- Explore the Jupyter Notebooks (e.g., `ml_premium_prediction_rest_with_gr.ipynb`) to view the data preprocessing, EDA, model training, and evaluation processes.

### Streamlit App
- Access the live application here: [Healthcare Premium Prediction App](https://healthcare-premium-predictions.streamlit.app/).
- Input customer details to get premium predictions.

## Results
- Achieved high model accuracy with minimal extreme prediction errors.
- Models include Linear Regression, Ridge Regression, and XGBoost.
- **Key metrics:**
  - Accuracy: >97%.
  - Percentage of errors within 10%: >95%.

## Contribution
Contributions are welcome! Feel free to submit issues or pull requests.

## Contact
For questions or collaboration:
- **Email:** akshada.bauskar171222@gmail.com


