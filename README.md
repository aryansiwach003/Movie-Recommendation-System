# 🎬 Movie Recommendation System

A content-based Movie Recommendation System built using **Python, Machine Learning, and Streamlit**.  
The system recommends similar movies based on movie metadata such as genres, keywords, cast, and crew, and displays movie posters using the TMDB API.

---

## 🚀 Features
- Content-based movie recommendations
- Uses cosine similarity on textual features
- Interactive web interface built with Streamlit
- Fetches movie posters using TMDB API
- Includes full data preprocessing & training notebook

---

## 🧠 Project Workflow
1. **Data Collection**
   - TMDB 5000 Movies Dataset
   - TMDB 5000 Credits Dataset

2. **Data Preprocessing**
   - Merge movies and credits datasets
   - Extract relevant features (genres, keywords, cast, crew, overview)
   - Clean and transform text data

3. **Feature Engineering**
   - Combine important features into a single text column
   - Vectorize text using CountVectorizer
   - Compute cosine similarity matrix

4. **Recommendation Logic**
   - Given a movie, find the most similar movies
   - Display top 5 recommendations with posters

5. **Web Application**
   - Built using Streamlit
   - Simple UI for movie selection and recommendations

---


## 📂 Project Structure
📁 movie-recommender-system
│
├── 📁 fronted
│   ├── app.py
│   └── 📁 datasets
│       ├── tmdb_5000_movies.csv
│       └── tmdb_5000_credits.csv
│
├── 📁 notebooks
│   └── movie-recommender-system.ipynb
│
├── movie_dict.pkl
├── movies.pkl
├── .gitignore
└── README.md
 ---

## 📊 Dataset
- **TMDB 5000 Movies**
- **TMDB 5000 Credits**

Datasets are included in the `datasets/` folder for reproducibility.

---

## 🧪 Jupyter Notebook
The notebook located at:
notebooks/movie-recommender-system.ipynb

covers:
- Data loading & exploration
- Feature extraction
- Text preprocessing
- Similarity computation

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the repository

git clone https://github.com/aryansiwach003/Movie-Recommendation-System.git
cd Movie-Recommendation-System/fronted
2️⃣ Install dependencies
pip install numpy pandas scikit-learn streamlit requests
3️⃣ Run the Streamlit app
streamlit run app.py

🔑 TMDB API Key

This project uses the TMDB API to fetch movie posters.

Create a TMDB account

Generate an API key

Add your API key inside app.py
https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn

Streamlit

TMDB API

Jupyter Notebook

🎯 Use Case

Learn content-based recommendation systems

Practice real-world ML project workflow

Build end-to-end ML + web application

Portfolio / Resume project

👤 Author

github.com/aryansiwach003






