# **Book Recommender System Using Machine Learning | Collaborative Filtering Based**


Recommendation systems are becoming increasingly important in today’s busy world. They help users make the right choices quickly, saving time and effort. 

A recommendation system searches for content that is interesting to an individual by analyzing factors like user profiles, browsing history, and similar users' preferences. It uses **Artificial Intelligence-based algorithms** to provide customized and relevant suggestions through **predictive modeling** and **heuristics**.

---

## **Types of Recommendation Systems**

### 1. **Content-Based**:
- Uses item attributes and characteristic information to make recommendations.
- Examples: Twitter, YouTube.
- **Approach**:
  - Focuses on user-specific actions and similar item recommendations.
  - Forms embeddings for features like genres, artists, etc.
  - Assumes if a user liked an item in the past, they will like similar items.
- **Limitation**: Can lead to excessive specialization, making obvious or overly narrow recommendations.

---

### 2. **Collaborative Filtering**:
- Based on user-item interactions.
- **Approach**:
  - Groups similar users based on ratings or comments.
  - Recommends items liked by users with similar preferences.
- **Use Case**: Book recommendation using clustering mechanisms.
- **Limitations**:
  - Computationally expensive due to the large user-item matrix.
  - Popular items dominate recommendations.
  - New or less popular items may never get recommended.

---

### 3. **Hybrid Systems**:
- Combines content-based and collaborative filtering to overcome their limitations.
- Modern systems use techniques like **word2vec** and **embedding models** to enhance accuracy.

---



## **Dataset Used**

- Dataset Link: [Book Recommendation Dataset on Kaggle](https://www.kaggle.com/ra4u12/bookrecommendation)

---

## **Concept Used: Nearest Neighbors**

The model is built using the **Nearest Neighbors algorithm**:

1. Load the dataset.
2. Initialize the value of **k** (number of neighbors).
3. Iterate through the dataset to calculate the distance between the test data and each training data point.
   - **Distance Metric**: Euclidean distance.
4. Sort the distances in ascending order.
5. Select the top **k** nearest neighbors.
6. Predict recommendations based on these neighbors.

---

## **How to Run Locally**

1. Clone the repository:
   ```bash
   git clone https://github.com/SubasishMula2001/Books_Recommender.git
   cd Books_Recommender
