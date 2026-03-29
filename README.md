🎬 Movie Recommendation System Using Machine Learning

This project builds a Movie Recommendation System using machine learning techniques to suggest movies based on user preferences. The system uses content-based filtering to find similarities between movies and recommend the most relevant ones.

📌 Objective
Recommend movies based on user input
Analyze movie features to find similarities
Improve user experience with personalized suggestions
🛠️ Tools & Libraries
Python
Pandas, NumPy
Scikit-learn (CountVectorizer, Cosine Similarity)
NLTK (for text preprocessing)
Streamlit (for web app)
📁 Dataset
tmdb_5000_movies.csv: Contains movie details like genres, keywords, overview
tmdb_5000_credits.csv: Contains cast and crew information
🔍 Workflow
Data Preprocessing
Merge movies and credits dataset
Handle missing values
Extract important features (genres, cast, crew, keywords)
Convert JSON-like data into readable format
Feature Engineering
Combine selected features into a single text column (tags)
Apply text cleaning and stemming
Vectorization
Convert text data into numerical vectors using CountVectorizer
Similarity Calculation
Compute cosine similarity between movie vectors
Recommendation System
Find top similar movies based on similarity score
Return top 5 recommended movies
📊 Sample Output
Input: Avatar
Output:
John Carter
Guardians of the Galaxy
Star Trek
Avengers
Interstellar
🚀 How to Run
Clone the repository

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py
📚 References
Scikit-learn documentation
TMDB dataset
NLP techniques for recommendation systems
💡 Future Improvements
Add collaborative filtering
Use deep learning models
Improve UI with better design
Add user-based recommendations
⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
