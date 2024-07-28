# Movie Recommendation System

A movie recommendation system built using Python, Pandas, and Scikit-learn. This project uses cosine similarity to recommend movies based on genres, keywords, tagline, cast, and director.


## Overview

This project demonstrates a simple movie recommendation system that suggests movies based on a user-input movie title. The system utilizes cosine similarity to find and recommend movies with similar attributes.

## Features

- Load movie data from a CSV file
- Pre-process movie data by filling missing values and combining selected features
- Convert text data to feature vectors using TF-IDF Vectorizer
- Calculate similarity scores using cosine similarity
- Recommend movies based on user input

## Setup Instructions

### Prerequisites

- Python 3.x
- Pandas
- Numpy
- Scikit-learn

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/movie-recommendation-system.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd movie-recommendation-system
    ```

3. **Install the required packages:**
    ```bash
    pip install pandas numpy scikit-learn
    ```

4. **Ensure you have the `movies.csv` file in the project directory.** This file should contain the movie dataset.

### Running the Project

1. **Run the Python script:**
    ```bash
    python movie_recommendation.py
    ```

## Usage

When prompted, enter the name of your favorite movie. The system will then suggest similar movies based on the entered movie name.

```plaintext
Enter your favourite movie name: The Matrix
Movies suggested for you:
1. The Matrix Reloaded
2. The Matrix Revolutions
3. ...
