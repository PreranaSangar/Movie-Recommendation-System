# 📽️ Movie Recommendation System

🧠 Overview

This project builds a Movie Recommendation System that suggests movies to users based on similarities in content such as genre, keywords, cast, and crew. It uses machine learning and natural language processing techniques to calculate similarity scores between movies and generate personalized recommendations.


🚀 Features

📊 Content-based filtering using cosine similarity

🎬 Recommendations based on movie metadata (title, genre, overview, etc.)

🧹 Data cleaning and preprocessing

🧩 Tokenization and feature extraction using CountVectorizer

🔍 Easy search functionality for movie titles

📈 Visualization of most similar movies

🧰 Technologies Used

Python 3.x

Jupyter Notebook

Libraries:
           pandas — for data manipulation
           numpy — for numerical operations
           scikit-learn — for feature extraction & similarity computation
           nltk — for text preprocessing
           ast — to parse complex data structures in the dataset

🗂️ Dataset

The project uses publicly available movie metadata such as:

Movie title

Overview

Genres

Cast and crew

You can download datasets like tmdb_5000_movies.csv and tmdb_5000_credits.csv from Kaggle - The Movies Dataset.

⚙️ How It Works

Data Preprocessing – Cleans the movie metadata, merges datasets, and extracts key features.

Feature Engineering – Combines text data (overview, genres, etc.) into a single “tags” column.

Vectorization – Converts text data into vectors using CountVectorizer.

Similarity Computation – Calculates similarity scores using cosine_similarity.

Recommendation Function – Suggests the top N most similar movies for a given title.

💾 Installation

Clone the repository and install dependencies:
git clone https://github.com/<PreranaSangar>/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt

🧩 Run the Project

Open the notebook in Jupyter:

jupyter notebook "Movie Recommendation System.ipynb"

📁 Project Structure
Movie Recommendation System/
│
├── Movie Recommendation System.ipynb
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
├── requirements.txt
└── README.md




           
