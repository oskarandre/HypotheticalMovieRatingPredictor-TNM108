# Movie Rating Predictor 2000

Have you ever had a genius idea for a movie or dreamt about becoming the next Spielberg, but don’t know if your ideas are good enough? We have. So, we decided, by using the power of machine learning and analysis, to create a system that can predict user ratings for a movie of your choice.

## Overview

Machine learning offers a promising solution for predicting the potential success and audience reception of a film. This project delves into the development and implementation of a movie rating prediction system using machine learning, with a focus on leveraging key movie features such as genre, actors, and plot.

Through the analysis of historical movie data and user ratings, we will explore how different genres, popular actors, and plots impact audience ratings. The goal is to create a predictive system that not only provides accurate forecasts of a film's potential success but also offers insights into how different genres and actors affect the score.

## Features

- Input details about a hypothetical movie: genre, lead actor, director, and a short summary of the plot.
- Compare the input movie to a large number of already existing movies and their ratings.
- Predict the potential user rating for the input movie.
- Provide insights into how similar movies have been rated.

## Usage

1. **Install Dependencies**: Ensure you have the required Python libraries installed.
    ```bash
    pip install numpy pandas PySimpleGUI scikit-learn
    ```

2. **Run the Predictor**: Execute the `Predictor.py` script to launch the GUI.
    ```bash
    python Predictor.py
    ```

3. **Input Movie Details**: Enter the genre, lead actor, director, and a short description of the plot in the GUI.

4. **Get Predictions**: The system will predict the user rating for your movie and show similar movies.

## Example

1. **Input**:
    - Genre: Action
    - Actor: Tom Cruise
    - Director: Steven Spielberg
    - Plot: A thrilling adventure of a secret agent.

2. **Output**:
    - Predicted Rating: 8.5
    - Similar Movies: "Mission Impossible", "Minority Report"


Will your movie be a blockbuster or forgotten on the back shelves of the rental store? Our movie rating predictor will give you a sneak peek into the future!
