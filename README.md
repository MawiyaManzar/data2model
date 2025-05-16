# Data2Model - Data Cleaning and Machine Learning Simulator
Explanation Video-https://youtu.be/LetBYlFo5qc
## Overview
## Home page
![WhatsApp Image 2025-05-16 at 21 58 36_b26b25ea](https://github.com/user-attachments/assets/2b429aed-f284-456b-8662-73569e3925b8)
## Data Preprocessing
![WhatsApp Image 2025-05-16 at 21 58 36_393c7d62](https://github.com/user-attachments/assets/74bfc637-cde0-4157-82bf-8419104ed363)
## Model Training
![WhatsApp Image 2025-05-16 at 21 58 37_4f6c060b](https://github.com/user-attachments/assets/8d5e911d-01a3-4ec7-bc76-115daa3dbc39)
## Data Visualization
![WhatsApp Image 2025-05-16 at 21 58 38_353e83a8](https://github.com/user-attachments/assets/fcbcd62e-3bba-47d5-ac8d-d44f274a125f)





**Data2Model** is a user-friendly Streamlit web application designed to streamline the process of data exploration, cleaning, preprocessing, model training, and prediction in machine learning.  Whether you're a beginner experimenting with different algorithms or a data enthusiast looking for a quick and interactive tool, Data2Model provides a visual and intuitive interface to work with your datasets.

**Key Features:**

*   **Interactive Data Loading:** Upload CSV or Excel files directly through the app's interface.
*   **Data Preview and Exploration:** View your data in a tabular format and generate comprehensive profiling reports for in-depth data understanding.
*   **Automated Data Cleaning:**
    *   Handle missing values using mean, median, or mode based on data distribution.
    *   Option to drop irrelevant columns.
*   **Intelligent Data Preprocessing:**
    *   **Scaling:** Automatically applies appropriate scaling techniques (Standardization, Min-Max, Robust Scaling) to numerical features based on normality tests and skewness.
    *   **Categorical Encoding:**  Offers a range of encoding methods for categorical features, including One-Hot Encoding, Ordinal Encoding (with user-defined order), Hash Encoding, and Frequency Encoding, adapting to feature cardinality and user preferences.
*   **Versatile Model Training:**
    *   Supports three problem types: **Classification, Regression, and Unsupervised Learning.**
    *   Provides a selection of popular machine learning algorithms for each problem type (see "Algorithms Implemented" section).
    *   Interactive parameter tuning for each algorithm using Streamlit sliders, selectboxes, and checkboxes.
    *   Clear descriptions and help text for each algorithm and parameter.
*   **Model Evaluation and Reporting:**
    *   **Classification:** Displays classification reports (precision, recall, F1-score, support) and confusion matrices.
    *   **Regression:** Presents key regression metrics (R-squared, Mean Absolute Error, Mean Squared Error, Root Mean Squared Error) with interpretations.
    *   **Unsupervised Learning:** Shows cluster labels (for clustering algorithms), explained variance ratio (for PCA), anomaly scores (for Isolation Forest), and interactive visualizations where applicable.
*   **Prediction Interface:**
    *   For supervised learning models, a user-friendly sidebar allows you to input feature values using selectboxes pre-populated with representative data values.
    *   Predicts the target variable based on the trained model and user-provided inputs.
    *   Displays predicted class (for classification) or predicted value (for regression).
*   **Code Download:**  Download the Python code snippet for the selected machine learning model, including parameter settings, enabling users to reuse or further customize the code.

## Getting Started

### Prerequisites

Before running Data2Model, ensure you have the following installed:

*   **Python 3.7+:**  Download from [python.org](https://www.python.org/downloads/).
*   **Pip:** Python package installer (usually included with Python installations).

**Recommended:**  It's highly recommended to create a virtual environment to keep your project dependencies isolated. You can use `venv` or `conda` for this.

**Example using `venv`:**

```bash




Enjoy using Data2Model! This application is intended to be a helpful tool for exploring data and experimenting with machine learning models. Please note that it's designed for educational and demonstrative purposes and may not be suitable for production-level, mission-critical applications without further testing and validation.


.
