# Salary Prediction ML App

This Flask-based web application predicts the salary of an employee based on their experience, test score, and interview score. It utilizes a machine learning model trained on the provided dataset.

## Getting Started

### Prerequisites

Ensure you have Python and pip installed. You can install them from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AsadShibli/flask_model_deploy/
    ```

2. Navigate to the project directory:

    ```bash
    cd flask_model_deploy
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Run the Flask app:

    ```bash
    python app.py
    ```

2. Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

3. Enter the required information: experience, test score, and interview score.

4. Click the "Predict" button to get the estimated salary.

### Project Structure

- **hiring.csv**: Dataset containing employee information.
- **model.py**: Python script to preprocess the data and train the machine learning model.
- **model.pkl**: Serialized trained model.
- **app.py**: Flask application script defining routes and handling predictions.
- **templates/index.html**: HTML template for the web interface.
- **requirements.txt**: List of Python dependencies.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or a pull request.

