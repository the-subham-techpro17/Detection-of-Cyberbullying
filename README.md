# Detection of Cyberbullying Using Machine Learning and Deep Learning Algorithms

This project provides a cutting-edge solution to detect cyberbullying in social media posts using advanced deep learning techniques, achieving an impressive accuracy of **95%** with LSTM architecture.

---

## 📜 Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [🏗️ Project Structure and Recent Updates](#project-structure-and-recent-updates)
4. [How It Works](#how-it-works)
5. [🛠️ Getting Started](#getting-started)
6. [Dataset](#dataset)
7. [Results](#results)
8. [🚀 Features and Future Enhancements](#features-and-future-enhancements)

---

## 📝 Introduction

Cyberbullying is a significant concern in today’s digital world. This project addresses the challenge by offering a robust tool to classify social media content into two categories: `bullying` and `No_bullying`. The solution leverages the power of LSTM-based deep learning models to achieve high accuracy and reliability.



## 🛠️ Technologies Used

- **Flask:** Backend framework for web application.
- **TensorFlow/Keras:** Deep learning library for building and training the LSTM model.
- **Pandas & NumPy:** For data manipulation and numerical operations.
- **HTML/CSS:** Frontend structure and design.
- **Pickle:** For saving and loading the tokenizer.

---

## 🏗️ Project Structure and Recent Updates

### Project Structure

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

### Recent Updates

- **Bulk Prediction Feature:** Allows users to upload datasets for batch analysis.
- **Improved Preprocessing:** Enhanced text cleaning and tokenization processes.
- **Performance Optimization:** Streamlined model loading and inference.

---

## 🔍 How It Works

1. **Preprocessing:**
   - Strips HTML tags and removes special characters.
   - Converts text to lowercase and tokenizes input.
   - Pads sequences to ensure uniform input length.

2. **Prediction:**
   - The cleaned text is fed into the pre-trained LSTM model.
   - The model outputs a prediction: `bullying` or `No_bullying`.

3. **Result Display:**
   - Users see results on a simple, intuitive web interface.

---

## 🛠️ Getting Started

### Prerequisites

- **Python 3.6+**
- Virtual Environment (optional but recommended)

### Installation Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/cyberbullying-detection.git
   cd cyberbullying-detection
   ```

2. **Set Up Virtual Environment:**

   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**

   ```bash
   python app.py
   ```

5. **Access the App:**

   Navigate to `http://127.0.0.1:5000/` in your web browser.

---

## 📊 Dataset

- **Sample Dataset:** A sample file (`upload.csv`) is included for testing.
- **Format:** Ensure the dataset contains a column `Id` for indexing and appropriate text columns.

---

## 📈 Results

- The model demonstrates an impressive accuracy of **95%**.
- Suitable for real-world applications with high reliability.

---

---

## 🚀 Features and Future Enhancements

### Current Features

- **Accurate Predictions:** Identifies whether a text contains bullying content.
- **Bulk Predictions:** Supports batch processing of uploaded datasets.
- **User-Friendly Interface:** Built using Flask for seamless interaction.
- **High Accuracy:** Achieves **95%** accuracy with the LSTM model.

### Future Enhancements

- **Multi-language Support:** Expand detection capabilities to multiple languages.
- **Real-time Monitoring:** Provide live API for real-time cyberbullying detection.
- **Advanced Visualizations:** Integrate interactive dashboards for detailed insights.
- **Enhanced NLP Techniques:** Incorporate transformers for improved accuracy.

---


