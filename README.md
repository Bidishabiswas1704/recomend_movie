# 🎬 Movie Recommendation System

## 🚀 Project Overview

Welcome to our Movie Recommendation System, where movie suggestions go beyond the ordinary. This intelligent application blends advanced recommendation strategies, including Collaborative Filtering, Content-Based Recommendation, and Non-Personalized Approaches, to curate a personalized and engaging movie-watching experience.

## 🔍 Problem Statement

Finding the perfect movie can be a challenge, especially for new users. Our system addresses this by seamlessly transitioning from non-personalized recommendations to advanced models. Whether you're a seasoned critic or a first-time viewer, our system adapts to your preferences.

## 🎯 Key Approaches and Features

### Non-Personalized Recommendations

- **IMDB Formula for Best Movies:**
  - Discover the cream of the crop across various genres using the renowned IMDB formula.

- **Most Commonly Watched Movie by Similar Users:**
  - Uncover hidden gems by exploring movies loved by users with similar tastes.

### Collaborative Filtering

- **Finding Similar Movies Based on Ratings:**
  - Dive into collaborative filtering, where the K Nearest Neighbors algorithm identifies movies with ratings similar to your taste.

  **Working Mechanism:**
  
  Collaborative Filtering operates on the principle of user similarity. By analyzing the preferences of users with similar movie-watching histories, the system suggests movies that align with your taste. The K Nearest Neighbors algorithm measures the proximity of user preferences, enhancing your movie recommendations.

### Content-Based Recommendation

- **Taking Genres Into Account:**
  - Elevate your movie night with content-based recommendations that consider the genres you love.

  **Working Mechanism:**

  Content-Based Recommendation focuses on the intrinsic features of movies, such as genres. By understanding your preferences through the genres you enjoy, the system predicts and suggests movies with similar content. This approach adds a layer of personalization based on the thematic elements that resonate with you.

## 📊 Key Aspects and Features
- 🤖 **Content-Based Recommendation:** Discover movies similar to your favorites using advanced natural language processing and cosine similarity.
- 👑 **Popularity-Based Recommendation:** Explore trending movies based on overall popularity and user ratings.
- 📊 **Data Analysis:** Dive into insightful visualizations exploring the world of movies, genres, and more.
- 🌐 **Streamlit Web App:** Explore movie recommendations interactively through our Streamlit web app. Tailor your preferences, and witness the system craft a unique movie playlist just for you.

## 🛠️ Technologies and Techniques Used
- 🐍 Python
- 📊 Pandas, NumPy, Matplotlib, Seaborn
- 🤖 Natural Language Processing with NLTK
- 🤖 Machine Learning with Scikit-Learn
- 🌐 Streamlit for Web App Development
- 📡 Requests for HTTP Handling



### Usage Instructions
**Get Started:**
1. 📥**Clone the repository:**
   ```bash
   git clone https://github.com/Bidishabiswas1704/recomend_movie.git
   ```

2. 🚀**Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. 🌐**Deployment:**
   ```bash
   streamlit run app.py
   ```
   Feel free to explore, contribute, and enhance the movie recommendation experience. Your movie night starts here! 🍿✨
   
5. **Open the web browser and go to [http://localhost:8501](http://localhost:8501) to explore the Movie Recommendation System.**

## 📊 Example Screenshots

![Screenshot 1](path/to/screenshot1.png)
*Caption: Fine-tuning preferences in the Streamlit app.*

![Screenshot 2](path/to/screenshot2.png)
*Caption: A personalized movie playlist based on user preferences.*

## 📂 Directory Structure

```
.
├── data/
│   └── tmdb_5000_movies.csv
├── notebooks/
│   └── Movie_Recommendation_System.ipynb
├── screenshots/
│   ├── screenshot1.png
│   └── screenshot2.png
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
└── .github/
    └── workflows/
        └── ci_cd.yml
```

## 🤝 Contribution

Contributions are more than welcome! Feel free to open issues, propose new features, or submit pull requests to enhance the Movie Recommendation System.

## Authors

- [@Bidisha_Biswas](https://www.github.com/Bidishabiswas1704)


## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy an immersive movie experience tailored just for you!





