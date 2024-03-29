# Movie_recommendation_system

This repository hosts an advanced movie recommendation system developed with Python and presented through a Streamlit frontend. It aims to deliver personalized movie suggestions by analyzing extensive movie datasets and user preferences. The system is built on a sophisticated data processing pipeline that includes cleaning, preprocessing, and feature engineering to ensure accurate recommendations.

## Key Features:
- **Personalized Recommendations:** Users can discover movies tailored to their tastes, based on genres, keywords, cast, and crew. <br />
- **Data-Driven Insights:** Leverages TMDB 5000 Movie Dataset for rich metadata on movies, including genres, cast, keywords, and overviews. <br />
- **Interactive UI:** Streamlit-powered interface provides a user-friendly platform for movie exploration. <br />
- **Advanced Data Processing:** Utilizes NLP techniques for preprocessing, including tokenization, stop word removal, lemmatization, and vectorization. <br />
- **Similarity-Based Recommendations:** Employs cosine similarity to find movies that closely match the user's preferences. <br />

### Backend Technologies:
**Pandas** for data manipulation and analysis. <br />
**Scikit-learn** for feature extraction and similarity computation. <br />
**NLTK** for natural language processing. <br />
**Ast** for safely evaluating strings containing Python literal structures. <br />

### Frontend Technologies:
**Streamlit** for creating the web app. <br />
**Requests for API calls** to fetch movie posters and additional details. <br />

## Getting Started:
- Clone this repository.
- Install required dependencies: pip install -r requirements.txt.
- Run the Streamlit app: streamlit run app.py.
- Explore movie recommendations by typing in a movie name or selecting from the dropdown.

## How It Works:
The system preprocesses movie metadata to extract meaningful features (genres, keywords, cast, crew, overview). These features are then combined into a single tag for each movie, which undergoes further NLP preprocessing (tokenization, stop word removal, lemmatization) before being vectorized. The cosine similarity between movie vectors is computed to identify the most similar movies for recommendations.

## Explore:
Dive into our movie recommendation system to find your next favorite movie. Contributions, suggestions, and feedback are welcome to improve the system further!
