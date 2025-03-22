# AI-POWERED-MEDICAL-DIAGNOSIS-SYSTEM


## Overview
This project is a **Multiple Disease Prediction System** built using **Streamlit**. It allows users to predict the likelihood of having **Diabetes, Heart Disease, or Parkinson's Disease** based on various medical inputs.

## Features
- **Diabetes Prediction**: Uses machine learning to predict whether a person has diabetes.
- **Heart Disease Prediction**: Determines the likelihood of heart disease based on medical parameters.
- **Parkinson's Disease Prediction**: Analyzes vocal characteristics to predict Parkinson's disease.
- **User-Friendly Interface**: Implemented using Streamlit for ease of use.
- **Tabbed Navigation**: Users can switch between different disease prediction sections.

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **Scikit-learn** (for machine learning model deployment)
- **Pickle** (for loading saved models)

## Installation & Setup
### Prerequisites
Ensure you have Python installed. You can download it from [Python's official website](https://www.python.org/).

### Install Required Libraries
Run the following command to install the necessary dependencies:
```bash
pip install streamlit scikit-learn streamlit-option-menu
```

### Running the Application
1. Clone the repository or copy the project files.
2. Navigate to the project directory.
3. Run the following command to start the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage
1. Select the disease prediction type from the sidebar.
2. Enter the required medical parameters.
3. Click the prediction button to get the result.

## Model Files
- `diabetes_model.sav` - Pre-trained model for diabetes prediction.
- `heart_disease_model.sav` - Pre-trained model for heart disease prediction.
- `parkinsons_model.sav` - Pre-trained model for Parkinson's disease prediction.

## Future Enhancements
- Improve the UI with better visualization.
- Add more disease prediction models.
- Integrate a database for user records.

## License
This project is open-source and available under the **MIT License**.

## Author
Developed by **Himanshu Yadav**.

