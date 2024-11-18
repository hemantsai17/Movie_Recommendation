# Movie Recommendation System (Content-Based Filtering)

This project implements a **Content-Based Movie Recommendation System** that recommends movies based on their **descriptions** or **plots**. The system uses **Bag of Words (BoW)** and **CountVectorizer** from the `scikit-learn` library to process movie descriptions and make recommendations by calculating the **cosine similarity** between movies.

![imgrecsys](https://github.com/user-attachments/assets/bf485fc2-d858-437f-a83d-48e32efcca56)

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
