# Movie Recommendation System#

# Overview

This project is a # Movie Recommendation System built using Jupyter Notebook for model development and Streamlit for a user-friendly web interface. It allows users to find personalized movie recommendations based on content similarity or collaborative filtering techniques.

# Features

**# Content-Based Filtering #** 
: Recommends movies similar to a given movie based on textual data like genre, cast, and plot.

**# Collaborative Filtering: #**
Recommends movies based on user preferences and ratings.

**# Interactive UI with Streamlit: #**
A clean and modern interface for easy movie search and recommendations.

**# Search Functionality: #**
Users can search for a movie and get recommendations instantly.

**# Visualization: #**
Charts and graphs to show trends in movie recommendations.

# Installation

# Prerequisites

* Make sure you have Python installed. Install the required libraries using:

pip install pandas numpy scikit-learn streamlit requests beautifulsoup4

Clone the Repository

git clone https://github.com/vikshittindwani/movie-recommended-system

Usage

 # 1. Model Development (Jupyter Notebook)

Open Movie_Recommendation.ipynb in Jupyter Notebook.

Run the cells to preprocess data, build models, and generate recommendations.

# 2. Running the Streamlit App

To launch the web interface, run the following command:

streamlit run app.py

Then open the provided # localhost URL in your browser.

Project Structure

movie-recommendation-system/
│── data/                   # Dataset files (CSV, JSON, etc.)
│── notebooks/              # Jupyter Notebook for model development
│── app.py                  # Streamlit application
│── model.py                # Recommendation logic (content-based & collaborative)
│── requirements.txt        # Dependencies
│── README.md               # Documentation

# Dataset

The dataset used is from # IMDb/TMDB containing movie titles, genres, descriptions, and ratings.

# Streamlit App
![image](https://github.com/user-attachments/assets/1c1dd3a0-a7e4-46aa-9981-e575a148bd32)

![image](https://github.com/user-attachments/assets/0ef4c282-68cd-45b4-8bc5-309da8bfccc3)


# Future Enhancements

Improve recommendation accuracy using # Deep Learning.

Add # user login and personalized recommendations.

Deploy on # Heroku/AWS.

Contributing

Feel free to fork the repository and submit pull requests!

License

This project is licensed under the # MIT License.

# Happy Movie Watching! 🎬🍿


