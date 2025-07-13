# 📚 Book Recommender System (Collaborative Filtering)

This project is a collaborative filtering-based book recommendation system built with Python. It suggests books to users based on similarities in user preferences and historical ratings.

## 🎯 Objective

To build a user-based recommendation engine using cosine similarity to recommend books, leveraging a real-world dataset of user-book interactions.

## 🧠 Key Features

- Collaborative filtering using user-user similarity
- Cosine similarity computation
- User-item matrix generation
- Evaluation using Mean Squared Error (MSE)
- Visualizations:
  - Rating distribution
  - User similarity heatmap
  - Most recommended books

## 📁 Dataset

- `books.csv`: Metadata about books
- `ratings.csv`: User-book rating interactions

> The dataset is assumed to be pre-cleaned and structured.

## 🔍 Project Structure

- **Step 1**: Problem Definition & Benefits
- **Step 2**: Data Loading
- **Step 3**: Exploratory Data Analysis (EDA)
- **Step 4**: Data Preparation (user-item matrix)
- **Step 5**: User Similarity Calculation (cosine)
- **Step 6**: Recommendation Evaluation (MSE)
- **Step 7**: Visualizations & Insights

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

## 📊 Sample Output

- Mean Squared Error (MSE): _(Displayed in notebook)_
- Heatmap of user similarities
- List of top-recommended books for sample users

## 🧪 Evaluation

The system was evaluated using Mean Squared Error (MSE) by comparing predicted ratings against actual user ratings in the test set.

## 📌 Future Improvements

- Implement item-based filtering
- Integrate content-based filtering (e.g. book genres)
- Deploy as a web app for interactive use
- Handle sparse matrix issues with advanced techniques like SVD

## 👤 Author

**Abdulrahman Adisa Amuda**  
Cohort 3 — AI/ML Track  
3MTT (Federal Government of Nigeria)

---

### 📎 License

This project is for educational purposes only.
