# Book Recommendation System 📚

This is a book recommendation system built using Python, Pandas, and scikit-learn.

## 🔹 How to Use
1. Clone this repo: [https://github.com/Mimo-a11y/Book-recomendation-system.git]

2. Install dependencies: numpy, pandas,scipy, scikit-learn, jupyter

3. Download or create a sample dataset:
- **Option 1:** Download the dataset from [https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset].
- **Option 2:** Create a sample dataset using:
  ```python
  import pandas as pd

  books_df = pd.DataFrame({
      'book_id': [1, 2, 3, 4, 5],
      'title': ["The Hunger Games", "Harry Potter", "Twilight", "To Kill a Mockingbird", "The Great Gatsby"]
  })

  user_ratings_df = pd.DataFrame({
      'user_id': [1, 2, 3, 4, 5],
      'book_id': [1, 2, 3, 4, 5],
      'rating': [5.0, 4.5, 4.0, 5.0, 3.5]
  })
  ```

4. Run the Jupyter Notebook.


