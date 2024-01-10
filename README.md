# Movie Recommender System

## Overview

This project implements a Movie Recommender System. It recommends movies based on Content based. The system uses the [TMDB (The Movie Database)](https://www.themoviedb.org/) API to fetch movie posters.

## Prerequisites

Make sure you have the required libraries installed. You can install them using the following:

```bash
pip install streamlit requests
```

## Setup

Clone the repository:

```bash
git clone https://github.com/your-username/movie-recommender-system.git
```
```bash
cd movie-recommender-system
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

## Files

`app.py`: Main Streamlit application for the Movie Recommender System.
`movie_list.pkl`: Pickled file containing movie data.
`similarity.pkl`: Pickled file containing relevant data/method details.
`requirements.txt`: List of Python dependencies.

## Usage

1.Run the Streamlit app using the instructions in the Setup section.

2.Select a movie from the dropdown menu.

3.Click the "Show Recommendation" button to get movie recommendations.


















