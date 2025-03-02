# Disease Prediction Web App

This Streamlit web application predicts the likelihood of heart disease, diabetes, and Parkinson's disease based on user-provided health data.

## Features

-   Interactive web interface using Streamlit.
-   Prediction models for heart disease, diabetes, and Parkinson's disease.
-   User-friendly input forms for health data.
-   Clear prediction results with success and error messages.
-   Uses pre-trained machine learning models (scikit-learn).

## Prerequisites

-   Python 3.7+
-   Streamlit
-   Scikit-learn (sklearn)
-   Pandas
-   NumPy
-   Pickle

## Installation

1.  Clone the repository:

    ```bash
    git clone <(https://github.com/Pragnavi07/DISEASE_OUTBREAK.git)>
    cd <repository_directory>
    ```

2.  Create a virtual environment (recommended):

    ```bash
    python -m venv .venv
    ```

3.  Activate the virtual environment:

    -   Windows: `.venv\Scripts\activate`
    -   macOS/Linux: `source .venv/bin/activate`

4.  Install dependencies:

    ```bash
    pip install streamlit scikit-learn pandas numpy
    ```

5.  Place the pre-trained models (`.sav` files) in the `Saved_Models` directory and images (`.png` and `.jpg` files) in the `Images` directory.

## Usage

1.  Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

2.  Open the provided URL in your web browser.

3.  Navigate through the tabs to predict different diseases.

4.  Fill in the required health data and click "Diagnose."

5.  View the prediction results.

## Model Files

The pre-trained models (`.sav` files) should be placed in the `Saved_Models` directory. The application also uses scaler files, which are also stored in this directory.

## Image Files

The `Images` directory should contain the logo and background images used in the application.

## Deployment

To deploy this app on Streamlit Community Cloud:

1.  Create a public GitHub repository.
2.  Push the code, model files, and image files to the repository.
3.  Go to [share.streamlit.io](https://share.streamlit.io/).
4.
