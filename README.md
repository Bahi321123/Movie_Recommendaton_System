# Movie_Recommendaton_System
 Movie Recommendation System (Content-Based Filtering)
About the Project
This is a simple movie recommendation system I made as part of my learning in Python and data science.
It recommends movies based on the similarity of their content like genres, cast, crew, and overview.
The idea was to understand how content-based filtering works and how we can use cosine similarity for recommendations.

Why I Made This Project
I wanted to learn how Netflix or IMDB shows “Because you watched…” recommendations.
Content-based filtering seemed like a good starting point, so I decided to try it myself using a public dataset.

Features
Takes a movie name from the user

Finds similar movies based on their content

Shows top recommendations

Dataset used: TMDB 5000 Movies Dataset

Technologies Used
Python

Pandas

NumPy

Scikit-learn (for CountVectorizer and Cosine Similarity)

How It Works
Load the dataset (movies.csv, credits.csv)

Merge them and extract important columns

Preprocess the data (remove nulls, clean text, convert lists to strings)

Convert text into vectors

Calculate cosine similarity

Return top N similar movies

How to Run
Download the dataset from Kaggle (TMDB 5000 Movies Dataset)

Put the CSV files in the same folder as the script/notebook

Run the Python file or open the .ipynb file in Google Colab

Enter a movie name when asked

Example
markdown
Copy
Edit
Enter a movie: Avatar
Top 5 similar movies:
1. John Carter
2. Guardians of the Galaxy
3. The Matrix
4. Star Trek
5. Thor
📌 Movie Recommendation System (Collaborative Filtering)
About the Project
This is another version of a movie recommendation system, but here the idea is different.
Instead of just looking at movie content, this one recommends movies based on ratings given by other users (collaborative filtering).
It tries to find patterns in user preferences and recommend accordingly.

Why I Made This Project
After making the first project, I realized that content-based filtering has a big limitation — it only suggests similar types of movies.
So I wanted to try collaborative filtering to get more varied recommendations, just like how real platforms suggest things you never even thought about.

Features
Works with user-movie rating data

Finds similar users or items

Gives recommendations even if you haven’t watched many movies

Dataset used: MovieLens dataset

Technologies Used
Python

Pandas

NumPy

Surprise Library (for collaborative filtering algorithms)

How It Works
Load the ratings dataset (MovieLens)

Train a collaborative filtering model (KNNBasic / SVD)

Predict ratings for movies a user hasn’t seen

Recommend the highest predicted rating movies

How to Run
Download the MovieLens dataset

Put the CSV file in the project folder

Run the Python file or .ipynb in Google Colab

Enter your user ID to get recommendations

Example
markdown
Copy
Edit
User ID: 5
Recommended Movies:
1. The Shawshank Redemption
2. The Godfather
3. The Dark Knight
4. Inception
5. Pulp Fiction
