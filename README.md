NextRead – AI Book Recommendation System

A Streamlit-based AI web application that provides personalized book recommendations based on book titles and genres using content-based filtering techniques.

Description

NextRead is an AI-powered book recommendation system designed to help users discover books tailored to their interests. The application analyzes book titles and genre tags using Natural Language Processing techniques such as TF-IDF and cosine similarity to generate relevant recommendations.

The project also includes a Model Performance Dashboard that visually compares different recommendation approaches using key evaluation metrics. This application is developed for educational and demonstration purposes.

Features

User-friendly Streamlit web interface

Book recommendations based on title similarity

Genre-based book discovery

Content-based filtering using NLP

Interactive model performance dashboard

Clean UI with multi-page navigation

Live Application

The application is deployed and hosted using Streamlit Cloud.

Access the live app here:

https://nextread123.streamlit.app/

Getting Started
Dependencies

Python 3.8 or higher

Operating System: Windows / macOS / Linux

Required Libraries

All required dependencies are listed in the requirements.txt file:

streamlit

pandas

numpy

scikit-learn

plotly

Installation

Clone the repository:

git clone https://github.com/akshayavardhini84/nextread.git


Navigate to the project directory:

cd nextread


Install dependencies:

pip install -r requirements.txt

Running the Application

Start the Streamlit app:

streamlit run Home.py


Open your browser and visit:

http://localhost:8501

Project Structure
book-recommendation/
│
├── Home.py                 # Main landing page
│
├── pages/
│   ├── Recommendation.py   # Book recommendation engine
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

Recommendation Approach

Title-Based Recommendation:
Uses TF-IDF vectorization on book titles and cosine similarity to find similar books.

Genre-Based Recommendation:
Recommends books based on selected genre tags extracted from the dataset.

Disclaimer

This project is developed for educational and learning purposes only.
Recommendations are based on dataset patterns and do not guarantee user preference accuracy.

Author

Akshaya Vardhini
Pre-Final Year M.Tech Integrated Software Engineering Student, VIT
Interests: Machine Learning | Data Science | Web Development

Acknowledgments

Kaggle Goodreads Book Dataset

Scikit-learn Documentation

Streamlit Community

Open-source Contributors
