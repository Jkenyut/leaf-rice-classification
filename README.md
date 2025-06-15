# Leaf Rice Disease Classification


<h3 align="center">🌾 An AI-Powered System for Classifying Rice Leaf Diseases 🌾</h3>

<p align="center">
  A web application developed for the Agriculture Informatics final project to classify rice leaf diseases using a machine learning model.
</p>

<p align="center">
  <!-- Badges/Shields -->
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-2.x-black?logo=flask" alt="Flask">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Figma-Design-purple?logo=figma" alt="Figma">
</p>

---

## About The Project

The **Leaf Rice Disease Classification** system is a web application that leverages a trained machine learning model to predict rice leaf diseases from uploaded images. Developed for an Agriculture Informatics final project, the application provides a user-friendly interface for farmers and agricultural professionals to quickly and efficiently identify potential diseases, aiding in timely crop management.

## ✨ Key Features

-   ✅ **Image-Based Classification:** Upload an image of a rice leaf to get an instant disease prediction.
-   ✅ **Machine Learning Integration:** Utilizes a trained `.h5` model built with TensorFlow/Keras.
-   ✅ **User-Friendly Web Interface:** A simple and intuitive UI for easy interaction.
-   ✅ **Robust Backend:** Built with Flask to handle image processing and model predictions.
-   ✅ **Clear Design Mock-up:** A well-defined UI/UX design available on Figma.

## 🎨 Mock-Up Design

The front-end design mock-up is available on Figma:
[**View Mock-Up**](https://www.figma.com/file/Ld18KowBshaZQiEGkiaFfB/Untitled?node-id=0%3A1&t=ACEYlJqaDMhtVGjd-1)

## 🛠️ Technologies Used

-   **Backend:** Python, Flask
-   **Frontend:** HTML, CSS, JavaScript
-   **Machine Learning:** TensorFlow/Keras
-   **Design:** Figma

## 🚀 Getting Started

Follow these steps to set up the project on your local machine.

### 1. Prerequisites

-   Python 3.8 or higher
-   pip (Python package installer)

### 2. Installation

1.  **Clone the Repository**:
    ```bash
    git clone [this repository URL]

    cd leaf-rice-disease-classification
    ```

2.  **Set Up a Virtual Environment** (Recommended):
    ```bash
    python -m venv venv
    # On Windows: venv\Scripts\activate
    source venv/bin/activate
    ```

3.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Up the Model**:
    -   Place your trained `model.h5` file in the `model/` directory.

### 3. Running the Application

Start the Flask server:
```bash
python app.py
```
Access the application at `http://localhost:5000` in your web browser.

## 📂 Directory Structure

-   **model/**: Contains the machine learning model and related scripts.
    -   `model.h5`: The trained machine learning model.
    -   `predict.py`: Script to load the model and perform predictions.
-   **templates/**: Stores HTML files for the front-end interface.
-   **static/**: Contains static assets like CSS and client-side JavaScript.
-   **app.py**: The main Flask back-end script.

## 📖 Usage

1.  Open the web application in your browser.
2.  Upload an image of a rice leaf using the interface.
3.  The system will process the image and display the predicted disease class.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  **Fork** the repository.
2.  Create a **Feature Branch** (`git checkout -b feature/NewPredictionLogic`).
3.  **Commit** your changes (`git commit -m 'feat: Add new prediction logic'`).
4.  **Push** to the Branch (`git push origin feature/NewPredictionLogic`).
5.  Open a **Pull Request**.

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [`LICENSE`](LICENSE) file for details.


## 📬 Contact

For inquiries or feedback, please contact the team:

-   **Widi Afandi:** [widiafandi58@gmail.com](mailto:widiafandi58@gmail.com)
-   **Satria Nur Saputro:** [satrianursaputro06@gmail.com](mailto:satrianursaputro06@gmail.com)
