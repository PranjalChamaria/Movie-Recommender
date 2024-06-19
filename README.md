
# Movie Recommendation Project

## Overview
This project utilizes Streamlit to create a simple web application for recommending movies based on cosine similarity. The recommendation engine calculates similarity scores between movies using vectorized representations of movie genres, overviews (synopsis), and cast/crew members. Cosine similarity is employed to determine how similar two movies are based on these features.

## Features
- **Input**: Users can choose a movie title from a library of around 500 titles to receive recommendations.
- **Recommendations**: Based on the input movie, the system recommends other movies that are most similar.
- **Movie Details**: Displays details such as title, overview, genres, and top cast/crew members for each movie.
- **Interactive Interface**: Streamlit provides an intuitive interface with options to interactively explore recommendations.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/PranjalChamaria/movie-recommendation.git
   ```
2. Navigate into the project directory:
   ```bash
   cd movie-recommendation
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open a browser and go to `localhost:8501` to see the app interface.
3. Enter the title of a movie you like in the input box.
4. Click the "Recommend" button to see similar movies.

## Data Sources
- **Movies Dataset**: The movie data used for this project includes information on titles, overviews, genres, and cast/crew members. This dataset was sourced from Kaggle (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).

## Technologies Used
- **Python**: Programming language used for data preprocessing, cosine similarity calculation, and app development.
- **Streamlit**: Framework used for building and deploying the web application.
- **Scikit-learn**: Library used for cosine similarity calculation and vectorization.
- **Pandas, NumPy**: Libraries used for data manipulation and numerical operations.
- **NLTK**: Library used for text processing, including stop word removal.
- **Pickle**: Library used for serializing Python objects, used here for saving trained models or preprocessed data.

