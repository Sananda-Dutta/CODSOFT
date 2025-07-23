# 🎬 Movie Rating Prediction | CODSOFT Task 2

## 📌 Project Overview
Predicts IMDB ratings (0-10 scale) using:
- **Features**: Director, Actors, Genres, Budget, Runtime
- **Model**: Random Forest Regressor (RMSE: 0.68)
- **Dataset**: [IMDB 5000 Movies](https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset)

## 🛠️ Installation
```bash
pip install -r requirements.txt
```

## 🚀 Usage
1. Download `movie_metadata.csv` from Kaggle
2. Place it in `/data` folder
3. Run:
```bash
jupyter notebook notebooks/movie_rating.ipynb
```

## 📊 Sample Results
![Rating vs Budget Plot](notebooks/rating_vs_budget.png)
