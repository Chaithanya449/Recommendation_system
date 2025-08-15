🎬 Movie Recommendation System
📌 Purpose

The purpose of this project is to build a simple Content-Based Movie Recommendation System that suggests movies similar to a user’s choice based on their descriptions.
This system helps users discover movies they might enjoy without relying on ratings or reviews — instead, it focuses on the content (plot/description) of each movie.

🛠 What I Did in This Project

Created a mini movie dataset containing movie titles and their plot descriptions.

Processed the text data to convert descriptions into numerical vectors using TF-IDF (Term Frequency – Inverse Document Frequency).

Used Cosine Similarity to compare the similarity between movies based on their plot descriptions.

Built a recommendation function that:

Takes a movie name as input.

Finds the most similar movies.

Returns the top 5 recommendations.

Made the search case-insensitive so it works regardless of capitalization.

🧰 Tools & Libraries Used

Python – Programming language.

Pandas – For handling and managing the dataset.

Scikit-learn (sklearn) – For:

TfidfVectorizer to convert text into vectors.

cosine_similarity to measure similarity between movies.

NumPy – For numerical operations.

✅ Achievements

Successfully built a working movie recommendation engine from scratch.

Achieved accurate and relevant recommendations for given movie inputs.

Designed the system to be simple, fast, and easy to understand — ideal for learning how recommendation systems work.

Learned and implemented key NLP techniques like TF-IDF and similarity metrics.
