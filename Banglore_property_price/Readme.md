# Real Estate Price Prediction Website

This repository contains a comprehensive data science project that walks through the step-by-step process of building a real estate price prediction website. The project is divided into three main components: 

1. **Model Building**: Using the Bangalore home prices dataset from Kaggle, we'll develop a predictive model using Python's `sklearn` library and linear regression.
2. **Flask Server**: We'll create a Python Flask server that loads the trained model and serves HTTP requests, allowing for real-time price prediction.
3. **Web Interface**: A frontend built with HTML, CSS, and JavaScript will be used to input property details (like square footage, number of bedrooms, etc.) and retrieve predicted prices via the Flask server.

## Project Components

### 1. Model Building
- **Tools & Libraries**:
  - Python
  - Numpy & Pandas for data cleaning and manipulation
  - Matplotlib for data visualization
  - Scikit-learn (Sklearn) for building the predictive model
- **Concepts Covered**:
  - Data loading and cleaning
  - Outlier detection and removal
  - Feature engineering
  - Dimensionality reduction
  - Hyperparameter tuning using GridSearchCV
  - Model evaluation using K-fold cross-validation

### 2. Flask Server
- **Tools & Libraries**:
  - Python Flask
- **Functionality**:
  - Loading the trained model
  - Handling HTTP requests
  - Returning predicted prices based on input data

### 3. Web Interface
- **Tools & Technologies**:
  - HTML for structure
  - CSS for styling
  - JavaScript for interactivity
- **Functionality**:
  - Form to input property details
  - AJAX calls to Flask server to retrieve predictions
  - Displaying predicted prices on the page

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or an IDE like Visual Studio Code or PyCharm
- Flask
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/hmairaj94/ML_Regression_project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ML_Regression_project
    ```

### Running the Project

1. **Model Training**: Open the Jupyter Notebook in the `Model` directory and follow the steps to train the model.
2. **Flask Server**: Start the Flask server by running:
    ```bash
    python server.py
    ```
3. **Web Interface**: Open `app.html` in your browser to interact with the web interface.

## Dataset

The dataset used in this project is the Bangalore home prices dataset available on Kaggle. You can download it [here](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data).

## Contributing!


Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you have any suggestions or improvements.


---

**Happy Coding!**
![Screenshot (55)](https://github.com/user-attachments/assets/1c3332d4-0577-4dc0-bb99-7075c5ff6210)
[Screenshot (54)](https://github.com/user-attachments/assets/530bf9b5-66a5-48b7-97d8-5321d3eead61)

