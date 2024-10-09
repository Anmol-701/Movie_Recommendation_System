# Movie Recommendation System

This is a movie recommendation system built using machine learning techniques and Streamlit for the user interface. The project suggests movies based on the similarity of other movies.

## Project Overview

This application uses a content-based filtering method for movie recommendation. It fetches movie posters and other data from the Movie Database API (TMDb) to give recommendations.

## Features

- Content-based movie recommendation system.
- Fetches movie posters via TMDb API.
- Interactive and user-friendly interface using Streamlit.

## Requirements

- Python 3.x
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Anmol-701/Movie_Recommendation_System.git
   cd Movie_Recommendation_System

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    


3. Run the Streamlit application:
    ```bash
    streamlit run app.py

# Usage
  - The application will open in your web browser.
  - Select a movie from the dropdown, and the app will recommend similar movies and display their posters.

# Notes
  - Make sure to have an active internet connection for fetching movie posters from the TMDb API.
  - Ensure that the movie_dict.pkl and similarity.pkl files are present in the models/ directory.