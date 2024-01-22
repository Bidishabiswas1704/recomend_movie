# 🎬 Movie Recommendation System

## 🚀 Project Overview

Welcome to our Movie Recommendation System, where movie suggestions go beyond the ordinary. This intelligent application blends advanced recommendation strategies, including Collaborative Filtering, Content-Based Recommendation, and Non-Personalized Approaches, to curate a personalized and engaging movie-watching experience.

## 🔍 Problem Statement

Finding the perfect movie can be a challenge, especially for new users. Our system addresses this by seamlessly transitioning from non-personalized recommendations to advanced models. Whether you're a seasoned critic or a first-time viewer, our system adapts to your preferences.


## 🔍 Recommendation Approaches

### A) Simple Recommender System - Average Weight

The Simple Recommender system offers universal movie suggestions by considering overall popularity and occasional genre preferences. This model prioritizes movies with higher popularity and critical acclaim, assuming they are more likely to be appreciated by the average audience.

**Implementation:**
- Movies are sorted based on ratings and popularity.
- Top movies from this sorted list are presented.
- Users can specify a genre for personalized recommendations.

**Mathematical Model (IMDB's Weighted Rating Formula):**

![image](https://github.com/Bidishabiswas1704/recomend_movie/assets/140384850/28d5a9c1-c5d4-4c85-9455-46ccc9997a31)


- **v:** Number of votes for the movie
- **m:** Minimum votes required to be listed in the chart (set at the 85th percentile)
- **R:** Average rating of the movie
- **C:** Mean vote across the entire dataset

**Functionality:**
- Create Top 250 movies chart.
- Develop charts tailored to specific genres.

### B) Content-Based Recommendation System

Enhance the personalization of recommendations with a Content-Based Recommendation engine. This engine calculates similarities between movies using specific criteria, suggesting movies that closely resemble a particular film enjoyed by the user.

**Focus Areas:**
- Movie Overviews
- Movie Cast
- Director
- Keywords
- Genre

**Working Mechanism:**
- Content-Based Recommendation focuses on intrinsic movie features, such as genres.
- Understand your preferences through the genres you enjoy.
- Predict and suggest movies with similar content, adding a layer of personalization based on thematic elements.


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



## 📄 Usage Instructions
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





