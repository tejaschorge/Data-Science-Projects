# 📖 Book Recommendation System

✨ **Welcome to My Book Recommendation System Project!**

Prepare to dive into a smart and elegantly designed Book Recommendation System built entirely in Python. This project showcases the seamless integration of collaborative filtering, content-based filtering, and hybrid recommendation strategies, all engineered to deliver highly personalized book suggestions based on individual user preferences and interaction history.

From parsing and cleaning complex datasets to building intuitive models and visualizing performance insights. It’s a complete journey through data preprocessing, machine learning, and real-world recommender systems

---

## 🔄 Workflow: Book Recommendation System


**1. Data Loading:**
   
   - Reads books_data.csv file.

   - Loads book information: bookID, title, authors, average_rating.


**2. Preprocessing:**
   
   - Converts average_rating column to numeric.

   - Creates a new book_content feature by combining title and authors.

   - Cleans and tokenizes text using TF-IDF Vectorizer with stopword removal.


**3. Similarity Computation:**
   
   - Computes cosine similarity on the TF-IDF matrix of book_content to measure textual closeness between books.


**4. Recommendation Function:**

   - Accepts a book title as input.

   - Retrieves the top 10 most similar books based on cosine similarity scores.


**5. Visualization:**

   - Plots histogram of average book ratings using Plotly.

   - Visualizes top 10 most prolific authors using horizontal bar chart.


**6. Prediction:**
   
   - Takes a user-provided book title.

   - Returns top 10 content-based book recommendations.

---


## 📊 Results

- The recommendation system effectively suggests relevant books based on content similarity using TF-IDF and cosine similarity.

- It performs well in identifying thematically related books from over 11,000 entries.

- The solution is ready for deployment in:

   - Book discovery engines

   - Personalized recommendation dashboards

   - Library or bookstore management tools


