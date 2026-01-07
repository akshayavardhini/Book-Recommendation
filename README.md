# Book Recommendation System

A machine learning–based web application that recommends books based on titles and genres using content-based filtering techniques.

## Description

The NextRead project focuses on helping users discover books tailored to their interests using Natural Language Processing techniques. The system analyzes book titles and genre tags to recommend similar books through content-based filtering. Multiple recommendation approaches are evaluated, and insights are visualized using an interactive model performance dashboard. The application is deployed as a Streamlit web app and is developed for educational and demonstration purposes.

## Features

* User-friendly Streamlit web interface
* Book recommendations based on title similarity
* Genre-based book discovery
* Content-based filtering using NLP techniques
* Interactive model performance dashboard

## Live Application

The application is already deployed and hosted using Streamlit.

Access the live app here:

```
https://nextread123.streamlit.app/
```

## Getting Started

### Dependencies

* Python 3.8 or higher
* Operating System: Windows / macOS / Linux

Required Python libraries:

* streamlit
* pandas
* numpy
* scikit-learn
* plotly

All required dependencies are listed in the `requirements.txt` file.

### Installing

Clone the repository:

```bash
git clone https://github.com/akshayavardhini84/nextread.git
```

Navigate to the project directory:

```bash
cd nextread
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Executing Program

Run the Streamlit application:

```bash
streamlit run Home.py
```

Open your browser and navigate to:

```
http://localhost:8501
```

Use the interface to explore book recommendations and model performance insights.

## Project Structure

```
book-recommendation/
│
├── Home.py                 # Main landing page
│
├── pages/
│   ├── Recommendation.py   # Book recommendation module
│   └── Dashboard.py        # Model performance dashboard
│
├── data/
│   ├── books.csv
│   ├── ratings.csv
│   ├── tags.csv
│   └── book_tags.csv
│
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

## Help

If you encounter issues while installing dependencies or running the application, try:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

Ensure Python is installed correctly and added to the system PATH.

## Disclaimer

This project is intended for educational and learning purposes only.
The recommendations are generated based on dataset patterns and may not reflect individual preferences.

## Authors

**Akshaya Vardhini**  
Pre-Final Year M.Tech Integrated Software Engineering Student, VIT  
Machine Learning | Data Science | Web Development  

## Acknowledgments

* Kaggle Goodreads Book Dataset
* Scikit-learn Documentation
* Streamlit Community
* Open-source Machine Learning Contributors
