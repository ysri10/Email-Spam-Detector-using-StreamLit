# SMS Spam Detection Web Application

## Description
This project is a web-based SMS Spam Detection application built using Flask for the backend. It utilizes machine learning models to classify incoming text messages as either spam or not spam. The application employs a pre-trained model saved as `model.pkl` and a TF-IDF vectorizer saved as `vectorizer.pkl` to process and predict SMS texts.

## Features
- Upload and classify SMS messages
- Real-time detection of spam messages
- Simple and user-friendly interface
- Deployed as a Flask web application

## Installation

### Prerequisites
Ensure you have Python 3.7 or later installed on your machine.

### Setup
1. Clone the repository or download the source files.
2. Navigate to the project directory.
3. Install the required dependencies by running:

```bash
pip install -r requirements.txt
```

## Running the Application
1. In the terminal, navigate to the project directory.
2. Run the Flask application using the following command:

```bash
python app.py
```

3. Open your web browser and visit:

```
http://127.0.0.1:5000
```

## File Descriptions
- **app.py** - The main Flask application that runs the web server and processes SMS input for classification.
- **model.pkl** - Pre-trained machine learning model used for spam detection.
- **vectorizer.pkl** - TF-IDF vectorizer used to transform text input for the model.
- **check.text** - Sample input text file for testing.
- **requirements.txt** - List of required Python packages and their versions.

## Dependencies
Below are some of the major dependencies required for this project (full list available in `requirements.txt`):
- Flask==2.2.5
- sklearn
- pandas
- nltk
- joblib
- tensorflow
- transformers
- numpy

## Usage
- Upload an SMS message through the web interface.
- The model will classify the SMS as either spam or not spam.
- The result is displayed immediately.

## Model Training
- The model was trained using a dataset of SMS messages with spam labels.
- TF-IDF vectorization was applied to preprocess the text data.
- A logistic regression classifier was used to train the model.

## Acknowledgements
- This project uses open-source machine learning tools and libraries such as Scikit-learn and TensorFlow.

