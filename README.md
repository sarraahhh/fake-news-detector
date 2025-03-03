# Fake News Detector

## Overview
This project is a **Fake News Detector** that predicts whether a given news article is **fake or real** using a **Machine Learning model**. It is built using **Flask** for the web interface and a **Naïve Bayes model** trained on text data.

## Features
- Upload or enter news text to check if it is fake or real.
- Uses **TF-IDF vectorization** to process text.
- Web interface built with **Flask** and **HTML/CSS**.
- Model trained using **Naïve Bayes Classifier**.
- Deployed locally via Flask.

## Tech Stack
- **Python** (Flask, scikit-learn, pandas, numpy, pickle)
- **Machine Learning** (TF-IDF Vectorization, Naïve Bayes Classifier)
- **Web Development** (HTML, CSS, Flask)

## Installation
To run this project locally, follow these steps:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Fake-News-Detector.git
cd Fake-News-Detector
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Flask App
```bash
python app.py
```
The app will run on `http://127.0.0.1:5000/`

## Project Structure
```
Fake-News-Detector/
│── model.pkl                 # Trained Naïve Bayes model
│── vectorizer.pkl            # TF-IDF vectorizer
│── app.py                    # Flask backend
│── templates/
│   ├── index.html            # Web interface
│── static/
│   ├── style.css             # Styling for the web page
│── README.md                 # Project documentation

```

## How It Works
1. **Preprocessing**: News text is vectorized using **TF-IDF**.
2. **Model Prediction**: The trained **Naïve Bayes model** predicts whether the text is **fake or real**.
3. **Web Interface**: Flask sends the prediction result back to the user via an **HTML page**.

## Example Usage
1. Open the web app.
2. Enter a news article in the text box.
3. Click **Check**.
4. The app will display whether the news is **Fake or Real**.

## Future Improvements
- Implement **Explainability Models** (LIME & SHAP).
- Enhance the web UI with **Bootstrap or React**.
- Deploy the app on **Heroku or AWS**.

## License
This project is open-source under the **MIT License**.


