# 🎬 Movie Recommendation System

A machine learning based movie recommendation system developed using Python and Google Colab that recommends movies based on user preferences, watch history, genres, and content similarity.

The system uses fuzzy string matching and content-based filtering techniques to suggest relevant movies from a dataset of 10,000+ movies.

---

## 🚀 Features

✅ Movie Recommendation Based on Genres  
✅ Content-Based Recommendation System  
✅ Fuzzy Matching for Incorrect Movie Names  
✅ Similar Movie Suggestions  
✅ User Preference Analysis  
✅ Natural Language Processing (NLP)  
✅ Stopword Removal using NLTK  
✅ Fast Similarity Search  
✅ Dataset of 10K+ Movies  

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- NLTK
- FuzzyWuzzy
- Google Colab
- Machine Learning

---

## 📂 Project Structure

```bash
Movie-Recommendation-System/
│
├── dataset/
│   └── movie.csv
│
├── notebooks/
│   └── movie_recommendation.ipynb
│
├── screenshots/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/pushpendrahub/Movie-Recommendation-System.git
```

---

### 2️⃣ Navigate To Project Directory

```bash
cd Movie-Recommendation-System
```

---

### 3️⃣ Install Required Libraries

```bash
pip install pandas
pip install scikit-learn
pip install nltk
pip install fuzzywuzzy
```

OR

```bash
pip install -r requirements.txt
```

---

## ▶️ Run The Project

Open Jupyter Notebook or Google Colab and run:

```bash
movie_recommendation.ipynb
```

---

## 📊 Recommendation Techniques Used

### 🔹 Content-Based Filtering
Recommends movies based on genres and movie overview similarity.

### 🔹 Fuzzy String Matching
Handles incorrect or partially typed movie names using FuzzyWuzzy.

### 🔹 NLP Preprocessing
Uses NLTK stopword removal for better text similarity processing.

---

## 🧠 Workflow

1. Load movie dataset
2. Clean and preprocess data
3. Remove stopwords using NLTK
4. Combine genres and overview into tags
5. Apply fuzzy matching
6. Recommend top similar movies

---

## 📸 Screenshots

Add screenshots inside:

```bash
screenshots/
```

Recommended screenshots:

### ✅ 1. Dataset Preview
Screenshot of:
```python
movies.head()
```
<img width="1328" height="371" alt="image" src="https://github.com/user-attachments/assets/5cca7bdf-7927-4a53-9f1c-3916de9e7b1e" />

File name:
```bash
<img width="1920" height="1039" alt="image" src="https://github.com/user-attachments/assets/e354963f-6490-42ae-9784-1ad11cf484de" />

```

---

### ✅ 2. Dataset Information
Screenshot of:
```python
movies.info()
```



File name:
```bash
<img width="774" height="348" alt="image" src="https://github.com/user-attachments/assets/8789ec04-bb4a-407c-b448-b032af1420a0" />

```

---

### ✅ 3. Recommendation Output
Screenshot of:
```python
recommend('Inception')
```

File name:
```bash
<img width="1175" height="329" alt="image" src="https://github.com/user-attachments/assets/a2a6f717-6f6b-4529-91ba-30667462d70c" />

```

---

### ✅ 4. Fuzzy Matching Example
Screenshot of:
```python
recommend('captan ')
```
<img width="947" height="342" alt="image" src="https://github.com/user-attachments/assets/18a0083c-fba0-4779-8bab-8efaf198e664" />


File name:
```bash
<img width="538" height="343" alt="image" src="https://github.com/user-attachments/assets/f2130ce9-922a-4017-a09a-6d41c53af390" />

```

This is VERY GOOD because it shows typo handling capability.

---

## 📷 Adding Screenshot In README

After uploading screenshots to:

```bash
screenshots/
```

Use:

```md
![Uploading image.png…]()

```

Example:

```md
## Recommendation Output

```

---

## 📈 Dataset Information

- Dataset contains 10,000+ movies
- Includes:
  - Movie Title
  - Genres
  - Overview
  - IDs

Dataset used for recommendation and similarity analysis.

---

## 👨‍💻 Author

### Pushpendra Singh

GitHub:
https://github.com/pushpendrahub

---

## 🚀 Future Enhancements

- Streamlit Web Application
- TMDB API Integration
- Collaborative Filtering
- User Login System
- Recommendation Dashboard
- Web Deployment

---

## 🔒 Security Note

Sensitive files and credentials are excluded using `.gitignore`.

---

## 📄 License

This project is developed for educational and learning purposes.
