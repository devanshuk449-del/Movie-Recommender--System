# Movie Recommender System

## Overview
This project implements a content-based movie recommendation system using movie metadata from the TMDB dataset.

## Dataset
TMDB movie metadata dataset containing information such as genres, keywords, overview, cast, and crew.

## Methodology
- Cleaned and preprocessed textual features
- Combined relevant metadata into a single feature space
- Applied vectorization techniques
- Calculated similarity scores using cosine similarity
- Recommended top-N similar movies based on input title

## Recommendation Type
Content-Based Filtering

## Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, Streamlit

## Limitations
- Does not consider user preferences
- Suffers from limited diversity in recommendations

## Future Improvements
- Collaborative filtering
- Hybrid recommendation system

