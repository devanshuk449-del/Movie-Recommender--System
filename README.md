#  Movie Recommender System

## Overview

A Content-Based Movie Recommendation System built using Python, Scikit-learn, and Streamlit. The system recommends movies similar to a selected movie by analyzing metadata such as genres, keywords, cast, crew, and movie overviews.



## Features

* Content-based movie recommendations
* Similarity calculation using Cosine Similarity
* Interactive web interface with Streamlit
* Fast recommendations using a precomputed similarity matrix
* Simple and user-friendly design



## Dataset

This project uses the TMDB 5000 Movies Dataset and TMDB 5000 Credits Dataset.

Dataset contains:

* Movie Title
* Genres
* Keywords
* Overview
* Cast
* Crew



## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle



## Project Workflow

### 1. Data Preprocessing

* Merged movie and credits datasets
* Handled missing values
* Extracted relevant features

### 2. Feature Engineering

Combined:

* Genres
* Keywords
* Cast
* Crew
* Overview

into a single textual representation.

### 3. Vectorization

Used CountVectorizer to convert textual data into numerical vectors.

### 4. Similarity Computation

Calculated cosine similarity between movies to identify similar content.

### 5. Recommendation Engine

Returns the Top 5 most similar movies based on the selected movie.



## Machine Learning Concepts Used

* Natural Language Processing (NLP)
* Feature Engineering
* Bag of Words Model
* Vectorization
* Cosine Similarity
* Content-Based Filtering



## Project Structure

movie-recommender-system/
│
├── app.py
├── movie_dict.pkl
├── similarity.pkl


## Installation

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows:

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## Results

The recommendation system successfully identifies movies with similar content based on metadata features and provides relevant recommendations in real time.



## Limitations

* Does not use user ratings.
* Cannot learn from user behavior.
* Limited to metadata-based recommendations.



## Future Enhancements

* Collaborative Filtering
* Hybrid Recommendation System
* User Personalization
* TMDB API Integration
* Cloud Deployment (AWS/Azure/Streamlit Cloud)


