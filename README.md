# Movie Recommendation System

A ML-powered movie recommender app built using cosine similarity + TMDB API + Streamlit.
Select a movie and get the top 5 similar recommendations with posters.

##  Features
*  ML-based similarity recommendations 
*  Fetch posters using TMDB API
* ⚫ Sleek Dark UI (custom CSS)
* ⚡ Instant 5-movie recommendations
* 📁 Uses TMDB 5000 movie dataset
* 🔥 Hover animations + stylish movie cards
 
## 🧠 How It Works
The system uses:
1. TMDB 5000 Movies Dataset
Contains:
* Title
* Genres 
*Overview
* Keywords
* Cast & Crew
* Movie ID

## 2. Data Processing (done in the notebook)
* Text cleaning
* Merging keywords, genres, cast, overview
* Creating a “tags” column
* Bag of words representation

## 3. ML Model
* Vectorization → CountVectorizer
* Similarity Matrix → Cosine Similarity
* Stored as → similarity.pkl

## Tech Stack
* Python
* Streamlit
* Pandas
* Pickle
* Requests
* Scikit-learn
* TMDB API

## Installation & Setup

1️⃣ Clone the repo
``` bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2️⃣ Create virtual environment
```bash
python -m venv venv
```

3️⃣ Activate environment
#### Windows
```bash
venv\Scripts\activate
```

#### Mac/Linux
```bash
source venv/bin/activate
```

4️⃣ Install requirements
```bash
pip install -r requirements.txt
```

5️⃣ Run Streamlit app
```bash
streamlit run app.py
```

## 📁 Project Structure
```bash
│── app.py
│── movie_list.pkl
│── similarity.pkl
│── tmdb_5000_movies.csv
│── tmdb_5000_credits.csv
│── Movie Recommender System.ipynb
│── requirements.txt
└── README.md
```

## Dataset 
* Dataset used: **TMDB 5000 Movies Dataset**\
* Available on
Kaggle : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## 🌐 Live Demo
https://movies-recommendation-bot.streamlit.app/

## 📸 Screenshots
![img alt](https://github.com/nikhil-kumarrr/images/blob/main/Screenshot%202025-12-12%20115959.png?raw=true)
![img alt](https://github.com/nikhil-kumarrr/images/blob/main/Screenshot%202025-12-12%20120021.png?raw=true)
