# 🎬 Movie Recommendation System

A content-based movie recommendation system built using Machine Learning and the TMDB 5000 Movies Dataset. The application recommends movies similar to a selected movie by analyzing metadata such as genres, keywords, cast, crew, and movie overviews.

## 🚀 Features

* Recommend movies based on similarity
* Interactive web interface built with Streamlit
* Content-based filtering using movie metadata
* Fast recommendation generation using cosine similarity
* Clean and user-friendly UI

## 📊 Dataset

This project uses the TMDB 5000 Movies Dataset, which contains information about:

* Movie titles
* Genres
* Keywords
* Cast
* Crew
* Overviews
* Ratings and popularity metrics

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Streamlit
* Pickle

## ⚙️ How It Works

1. Movie and credits datasets are merged.
2. Relevant features such as genres, keywords, cast, crew, and overview are extracted.
3. Text preprocessing and feature engineering are performed.
4. A combined "tags" feature is created for each movie.
5. Count Vectorization converts text into numerical vectors.
6. Cosine Similarity measures similarity between movies.
7. The most similar movies are recommended to the user.

## 📁 Project Structure

```
Movie_Recommendation_System/
│
├── app.py
├── movie_list.pkl
├── similarity.pkl
├── requirements.txt
├── tmdb_5000_movies.csv
├── tmdb_5000_credits.csv
└── README.md
```

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie_Recommendation_System.git
cd Movie_Recommendation_System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## 🎯 Future Improvements

* Hybrid recommendation system
* Movie posters and trailers integration
* User authentication
* Personalized recommendations
* Deployment on Streamlit Cloud

## 👨‍💻 Author

**Habib Rehman Janwiri**

Computer Systems Engineering Student | AI & Machine Learning Enthusiast

Interested in Machine Learning, Generative AI, AI Agents, and Artificial General Intelligence (AGI).

## 📜 License

This project is developed for educational and learning purposes.
