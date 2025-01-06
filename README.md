# Detection of Cyberbullying Using Machine Learning and Deep Learning Algorithms

This project aims to detect instances of cyberbullying in social media posts using the LSTM architecture, achieving an accuracy of **95%**.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)


## Introduction

Cyberbullying is a pervasive issue in the digital age. This project provides a tool to classify social media content into two categories: `bullying` and `No_bullying`. The model utilizes deep learning techniques, specifically LSTM, for text classification.

## Features

- Predicts whether a given text contains bullying content.
- Allows bulk predictions using uploaded datasets.
- Displays a user-friendly interface with Flask web framework.
- Achieves high accuracy of **95%**.

## Technologies Used

- **Flask** for the web application.
- **TensorFlow/Keras** for building the LSTM model.
- **Pandas** for data manipulation.
- **NumPy** for numerical computations.
- **HTML/CSS** for the frontend.
- **Pickle** for saving and loading the tokenizer.

## Folder Structure

```
project_root/
|-- app.py                    # Main Flask application
|-- lstms.h5                  # Pre-trained LSTM model
|-- tokenizer.pickle          # Tokenizer for preprocessing text
|-- templates/                # HTML templates for Flask
|   |-- index.html            # Homepage
|   |-- chart.html            # Chart page
|   |-- upload.html           # File upload page
|   |-- preview.html          # Data preview page
|   |-- prediction.html       # Prediction results page
|   |-- performance.html      # Model performance page
|-- static/                   # Static files (CSS, JS, Images)
|-- Accuracy.txt              # Model accuracy details
|-- upload.csv                # Sample upload dataset
|-- test.csv                  # Test dataset
|-- README.md                 # Project documentation
```

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kumar/cyberbullying-detection.git
   cd cyberbullying-detection
   ```

2. **Create a virtual environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   python app.py
   ```

5. **Access the application:**

   Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Usage

1. **Homepage:** Navigate to the homepage to explore the project features.
2. **Upload Dataset:** Upload a `.csv` file to preview and predict bullying content.
3. **Prediction:** Enter text manually or use the bulk prediction feature.

## Dataset

- The sample dataset file is available as `upload.csv`.
- Ensure the dataset contains a column named `Id` for indexing.

## Results

- The LSTM model achieves an accuracy of **95%**.


