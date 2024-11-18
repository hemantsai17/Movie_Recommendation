# Movie Recommendation System (Content-Based Filtering)

This project implements a **Content-Based Movie Recommendation System** that recommends movies based on their **descriptions** or **plots**. The system uses **Bag of Words (BoW)** and **CountVectorizer** from the `scikit-learn` library to process movie descriptions and make recommendations by calculating the **cosine similarity** between movies.

![imgrecsys](https://github.com/user-attachments/assets/bf485fc2-d858-437f-a83d-48e32efcca56)

## Goal

The goal of this project is to build a movie recommendation system that can suggest similar movies to users based on the textual content (such as descriptions, genres, or plot summaries) of the movies. By leveraging natural language processing (NLP) techniques like **Bag of Words (BoW)** and **CountVectorizer**, the system determines the similarity between movie descriptions and suggests the top recommended movies accordingly.

Key objectives:
- Build a content-based recommendation system that recommends movies similar to a given movie.
- Utilize **CountVectorizer** to convert movie descriptions into numerical vectors.
- Compute cosine similarity to measure the similarity between movie vectors.
- Provide a user-friendly interface to query and recommend movies based on their descriptions.


## Features

- **Content-based filtering**: Recommends movies based on the similarity of their descriptions or plot summaries.
- **Bag of Words (BoW)**: A text representation technique that converts movie descriptions into numerical vectors based on word frequency.
- **CountVectorizer**: Used to convert the text descriptions into feature vectors (tokens).
- **Cosine similarity**: Measures the similarity between movies based on their BoW vectors to recommend similar movies.

## Prerequisites

Before running the project, ensure you have Python 3.x installed along with `pip` for package management.

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
