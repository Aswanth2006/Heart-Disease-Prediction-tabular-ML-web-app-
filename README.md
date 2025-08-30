# Heart Disease Prediction - ML Web App

A machine learning web application built with Flask that predicts the risk of heart disease based on 13 clinical features from the UCI Cleveland dataset. It features a responsive user interface, a accurately trained model, and clean, scalable code for easy deployment.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-2.3%2B-black?logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-orange?logo=scikit-learn)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3%2B-purple?logo=bootstrap)
![License](https://img.shields.io/badge/License-MIT-green)

## 🌟 Features

-   **User-Friendly Web Interface:** Intuitive form for inputting patient clinical data, built with HTML, CSS, and Bootstrap for a clean and responsive experience.
-   **Accurate ML Model:** Powered by a model trained on the reliable UCI Cleveland heart disease dataset.
-   **Robust Backend:** Built with Python and Flask, ensuring clean, modular, and scalable code.
-   **Easy Deployment:** Ready to be deployed on platforms like Render, Heroku, or run on local servers.

## 📂 Tech Stack

-   **Frontend:** HTML, CSS, Bootstrap
-   **Backend:** Python, Flask
-   **Machine Learning:** scikit-learn, pandas, numpy
-   **Data Visualization & Analysis:** matplotlib, seaborn

## 📊 Dataset

-   **Source:** [UCI Machine Learning Repository - Heart Disease Dataset (Cleveland)](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
-   **Details:** 303 records with 13 clinical features and a target label indicating the presence (1) or absence (0) of heart disease.
-   **Key Features:** age, sex, chest pain type (cp), resting blood pressure (trestbps), cholesterol (chol), fasting blood sugar (fbs), resting electrocardiographic results (restecg), maximum heart rate achieved (thalach), exercise induced angina (exang), ST depression (oldpeak), slope of the peak exercise ST segment (slope), number of major vessels (ca), thalassemia (thal).

## ⚙️ Installation & Setup

Follow these steps to run this project locally.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Heart-Disease-Prediction-tabular-ML-web-app-.git
    cd Heart-Disease-Prediction-tabular-ML-web-app-
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    # On Windows
    python -m venv venv
    .\venv\Scripts\activate

    # On macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Flask application:**
    ```bash
    python app.py
    ```

5.  **Open your browser and visit:**
    `http://127.0.0.1:5000`

## 🖼️ Screenshots

| Homepage / Input Form | Prediction Result |
| :---: | :---: |
| ![Homepage Screenshot](static/images/screenshot-form.png) | ![Result Screenshot](static/images/screenshot-result.png) |
*<!-- Add your actual screenshots to a folder like `static/images/` and update these links. -->*

## 📈 Project Workflow

1.  **Data Preprocessing:** Loaded and cleaned the dataset, handled missing values, and performed feature scaling/normalization.
2.  **Model Training & Evaluation:** Trained and compared multiple algorithms (e.g., Logistic Regression, Random Forest). The best performing model was selected, evaluated using metrics like accuracy and F1-score, and serialized for use in the app.
3.  **Web Application Development:**
    -   **Backend (Flask):** Set up routes (`app.py`) to handle the homepage, form processing, prediction logic, and result display.
    -   **Frontend (Jinja2 Templates):** Created HTML templates for forms and results, styled with Bootstrap and custom CSS.
4.  **Testing & Deployment:** Tested the application locally and prepared it for deployment on a cloud platform.

## 🚀 Deployment

This app is configured for easy deployment on **Render** or **Heroku**.

### Deployment to Render (Recommended)
1.  Ensure your `requirements.txt` file is up to date.
2.  Create a `render.yaml` file or connect your GitHub repo directly to Render.
3.  Set the build command to `pip install -r requirements.txt` and the start command to `gunicorn app:app`.

*For detailed deployment guides, please check the official documentation of your chosen platform.*

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please follow these steps:

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## 🙌 Acknowledgments

-   Data provided by the UCI Machine Learning Repository.
-   Thanks to the contributors and maintainers of Flask, scikit-learn, and Bootstrap.
