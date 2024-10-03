# **Multiple Disease Prediction System**

## **Overview**

This project is a **Multiple Disease Prediction System** that uses machine learning models to predict the likelihood of three major health conditions:
- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

The system takes input from users based on medical data and applies pre-trained machine learning models to predict if the user may have any of the mentioned diseases. This tool can be useful for early-stage diagnosis and understanding health risks, ultimately aiming to improve healthcare outcomes.

## **Features**
- Predicts the likelihood of **Diabetes**, **Heart Disease**, and **Parkinson's Disease** using machine learning.
- User-friendly web interface built with **Streamlit** for easy input and display of results.
- Uses models trained on real-world datasets to make predictions based on user input.

## **Technologies Used**
- **Python** for backend programming.
- **Streamlit** for creating the web interface.
- **Scikit-learn** for machine learning model training and predictions.
- **Pickle** for loading pre-trained models into the application.

## **Input Parameters**

1. **Diabetes Prediction**:
   - **Pregnancies**: Number of pregnancies the person has had.
   - **Glucose**: Plasma glucose concentration.
   - **Blood Pressure**: Diastolic blood pressure (mm Hg).
   - **Skin Thickness**: Triceps skin fold thickness (mm).
   - **Insulin**: 2-hour serum insulin (µU/mL).
   - **BMI**: Body mass index (weight in kg / height in m²).
   - **Diabetes Pedigree Function**: A function that scores the likelihood of a person being diabetic based on family history.
   - **Age**: Age of the person.

2. **Heart Disease Prediction**:
   - **Age**: Age of the person.
   - **Sex**: Gender of the person (1 = male, 0 = female).
   - **Chest Pain Type**: Type of chest pain (ranging from 0 to 3).
   - **Resting Blood Pressure**: Blood pressure value (mm Hg).
   - **Cholesterol**: Serum cholesterol in mg/dl.
   - **Fasting Blood Sugar**: Blood sugar level greater than 120 mg/dl.
   - **Resting Electrocardiographic Results**: Electrocardiographic results (0, 1, 2).
   - **Maximum Heart Rate Achieved**: Maximum heart rate during exercise.
   - **Exercise Induced Angina**: Whether the person has exercise-induced angina (1 = yes, 0 = no).
   - **ST Depression Induced by Exercise**: Depression of the ST segment during exercise.
   - **Slope of the Peak Exercise ST Segment**: Slope of the ST segment.
   - **Major Vessels Colored by Fluoroscopy**: Number of major vessels colored by fluoroscopy.
   - **Thal**: A blood disorder that indicates possible heart disease (0 = normal, 1 = fixed defect, 2 = reversible defect).

3. **Parkinson’s Disease Prediction**:
   - **MDVP:Fo(Hz)**: Fundamental frequency.
   - **MDVP:Fhi(Hz)**: Maximum frequency.
   - **MDVP:Flo(Hz)**: Minimum frequency.
   - **MDVP:Jitter(%)**: Variation in fundamental frequency.
   - **MDVP:Jitter(Abs)**: Absolute jitter.
   - **MDVP:RAP**: Relative average perturbation.
   - **MDVP:PPQ**: Pitch period perturbation.
   - **Jitter:DDP**: Differences of differences in pitch period perturbation.
   - **MDVP:Shimmer**: Variation in amplitude.
   - **MDVP:Shimmer(dB)**: Shimmer in dB.
   - **Shimmer:APQ3**: Shimmer in amplitude perturbation.
   - **Shimmer:APQ5**: Shimmer in 5-point average.
   - **MDVP:APQ**: Average perturbation quotient.
   - **Shimmer:DDA**: Derivative of amplitude.
   - **NHR**: Noise-to-harmonics ratio.
   - **HNR**: Harmonics-to-noise ratio.
   - **RPDE**: Recurrence period density entropy.
   - **DFA**: Detrended fluctuation analysis.
   - **spread1**: Spread in the first dimension.
   - **spread2**: Spread in the second dimension.
   - **D2**: A measure related to fractal dimension.
   - **PPE**: Pitch period entropy.

## **Installation**

To get this project up and running on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Multiple-Disease-Prediction-System.git
   cd Multiple-Disease-Prediction-System
   ```

2. **Install the required libraries**:
   It is recommended to create a virtual environment, then install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Running the application**:
   You can run the web app using Streamlit:
   ```bash
   streamlit run app.py
   ```

4. **Visit the app**:
   Once the app starts, open a web browser and visit:
   ```
   http://localhost:8501
   ```

## **How to Use**
1. On the homepage, select the disease prediction model (Diabetes, Heart Disease, or Parkinson's Disease) from the sidebar.
2. Enter the required parameters based on the disease model you’ve selected.
3. Click on the **Test Result** button to get the prediction.
4. The result will be displayed on the page, showing whether the person is at risk for the disease or not.

---

## **Contributing**

Feel free to fork this project and contribute! If you have ideas for improvement or bug fixes, please submit a pull request.

---
