# SpamShield: SMS Spam Detection

## Overview
SpamShield is an AI-powered SMS spam detection system that analyzes incoming messages and classifies them as spam or legitimate. Built with Python and Machine Learning, this application provides accurate spam detection through a web interface.

**Live Demo:** [SpamShield](https://spam-shield-dz46.onrender.com/)

## Tech Stack
- **Programming Language:** Python
- **ML Libraries:** Scikit-learn, Pandas, NumPy
- **Web Framework:** Streamlit

## Features
- Real-time SMS spam classification
- Machine learning-based predictions
- Web-based user interface
- High precision spam detection

## Data Processing
**Dataset:** [Kaggle SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) containing 5,500+ labeled SMS messages

**Preprocessing Steps:**
- Handling missing and duplicate values
- Label encoding
- Text tokenization
- Removing special characters, stopwords, and punctuation
- Text normalization (lowercase conversion)
- Stemming for feature extraction

## Model Development
Multiple classifiers were evaluated:
- Naïve Bayes
- Random Forest
- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression
- ExtraTreesClassifier
- Support Vector Classifier (SVC)

**Result:** Achieved 100% precision for spam detection

## Installation & Usage

### Clone the Repository
```bash
git clone https://github.com/roysamarpita19/SpamShield.git
cd SpamShield
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
streamlit run app.py
```

## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests at the [GitHub repository](https://github.com/roysamarpita19/SpamShield.git).
