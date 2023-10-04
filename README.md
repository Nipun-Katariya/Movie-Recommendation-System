# Movie Recommendation System with Flask

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

A movie recommendation interface designed using Flask, HTML & CSS. Utilizes TfidfVectorizer to recommend the top 10 movie titles based on an input keyword or phrase. Uses the OMDb API for retrieving movie information.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is a movie recommendation system that takes user input in the form of a keyword or phrase and suggests the top 10 movie titles related to that input. It uses the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization technique to analyze the relevance of keywords and phrases to movie titles.

The project also leverages the OMDb (Open Movie Database) API to fetch detailed information about movies, including their titles, release years, directors, and ratings.

## Features
- User-friendly web interface built with Flask, HTML, and CSS.
- Movie recommendation based on user input.
- Display of movie details, including title, year, director, and rating.
- Seamless integration with the OMDb API for movie information retrieval.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/movie-recommendation.git
```
2. Change to the project directory:
```bash
cd Movie-Recommendation-System
```
