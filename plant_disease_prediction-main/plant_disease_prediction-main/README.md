# plant_disease_prediction
# Plant Disease Prediction System

This project is a web application that uses a deep learning model to predict plant diseases from leaf images. It's built with Streamlit for the user interface and TensorFlow for the machine learning model. The application also includes multi-language support for accessibility.

## Features

* **Image Upload:** Users can upload a leaf image for disease detection.
* **Disease Prediction:** The system predicts the plant disease and provides a confidence score.
* **Multi-Language Support:** The UI and disease descriptions can be translated into Hindi, Telugu, Tamil, Kannada, and Malayalam, in addition to English.
* **Disease Information:** For detected diseases, the application provides a description and a link to a relevant YouTube video (if available) for more information or treatment guidance.

## Technologies Used

* [cite_start]**Framework:** Streamlit [cite: 1]
* [cite_start]**Machine Learning:** TensorFlow [cite: 1] (for loading and running the deep learning model)
* [cite_start]**Image Processing:** Pillow (PIL Fork) [cite: 1]
* [cite_start]**Numerical Operations:** NumPy [cite: 1]
* [cite_start]**Translation:** Googletrans [cite: 1]
* **Data Handling:** JSON

## Setup and Installation

Follow these steps to get the project up and running on your local machine.

### 1. Prerequisites

* **Python 3.x:** Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).

### 2. Project Setup

1.  **Clone the Repository:**
    ```bash
    git clone <your_repository_url>
    cd plant-disease-prediction-system # Or whatever your project folder is named
    ```
    (Replace `<your_repository_url>` with the actual URL of your GitHub repository.)

2.  **Create a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    ```

3.  **Activate the Virtual Environment:**
    * **On Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **On macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

### 3. Model and Data Files

Ensure you have the following files in your project directory:

* `plant_disease_model.h5`: This is your trained deep learning model. (Note: This file is not provided in the prompt, but it's essential for the application to run.)
* `class_indices.json`: Contains the mapping of class indices to disease names.
* `disease_resources.json`: Contains descriptions and video links for various diseases.

### 4. Run the Application

```bash
streamlit run app.py
