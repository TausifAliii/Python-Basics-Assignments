# Anime Recommendation System Using Cosine Similarity

## Project Overview
This project is based on building an Anime Recommendation System using cosine similarity. The system recommends anime titles that are similar to a selected anime based on features such as genre, type, rating, and number of episodes.

Recommendation systems are widely used in platforms like Netflix, YouTube, Spotify, and Amazon. In the same way, this project helps users discover anime that are similar to the anime they already enjoy.

---

## Objective
The main objective of this project is to build a recommendation system using cosine similarity on an anime dataset.

The recommendation system compares anime based on:
- Genre
- Anime Type
- Rating
- Number of Episodes

The final output is a list of anime that are similar to the selected anime.

---

## Dataset Description
The dataset contains information about different anime titles.

### Columns Present in Dataset
- anime_id → Unique ID for each anime
- name → Anime title
- genre → Genre of the anime
- type → Anime broadcast type such as TV, OVA, Movie, etc.
- episodes → Number of episodes
- rating → Average user rating
- members → Number of community members

---

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Steps Performed

### 1. Data Loading
The anime dataset was loaded into a pandas DataFrame.

### 2. Data Understanding
The structure of the dataset was checked using:
- head()
- info()
- describe()
- isnull()

### 3. Data Cleaning
- Removed duplicate rows
- Filled missing values
- Converted episodes column into numeric format

### 4. Exploratory Data Analysis
Different graphs were created to understand:
- Rating distribution
- Anime type distribution
- Popular genres
- Correlation between numeric columns

### 5. Feature Engineering
Genre, type, rating, and episodes were combined into one column called combined_features.

### 6. Text Vectorization
CountVectorizer was used to convert text data into numerical format.

### 7. Similarity Calculation
Cosine similarity was used to measure similarity between anime.

### 8. Recommendation Function
A custom function was created to recommend similar anime based on cosine similarity scores.

### 9. Threshold Testing
Different threshold values were tested to check how the number of recommendations changes.

### 10. Performance Analysis
The strengths and limitations of the recommendation system were analyzed.

---

## Key Features
- Content-based recommendation system
- Cosine similarity implementation
- Missing value handling
- Data visualization
- Feature engineering
- Threshold testing
- Performance analysis

---

## Sample Recommendation
If the user searches for Naruto, the system may recommend anime such as:
- Bleach
- One Piece
- Fairy Tail
- Dragon Ball Z
- Hunter x Hunter

---

## Areas of Improvement
The current system only uses anime features. In the future, the system can be improved by:
- Adding user watch history
- Using collaborative filtering
- Using user ratings and reviews
- Using TF-IDF instead of CountVectorizer
- Building a web app using Streamlit or Flask

---

## Real-World Use Case
Recommendation systems are used by :contentReference[oaicite:0]{index=0}, :contentReference[oaicite:1]{index=1}, :contentReference[oaicite:2]{index=2}, and :contentReference[oaicite:3]{index=3}.

This anime recommendation system can help users discover similar anime quickly and improve their viewing experience.

---

## Files Included
- assignment_16_anime_recommendation.ipynb
- anime.csv
- README.md

---

## Conclusion
This project successfully builds an anime recommendation system using cosine similarity. It recommends anime based on genre, type, rating, and episodes.

This project is useful for understanding how recommendation systems work in real-world platforms and how machine learning can be applied in entertainment and content discovery systems.

---

## Author
Tausif Ali
