# Movie-Recommendation-with-Collaborative-Filtering

## 📌 Project Overview
This project builds a **Netflix Movie Recommendation System** using collaborative filtering. It analyzes user rating patterns to generate personalized movie suggestions based on similarity in preferences. The model leverages **Truncated SVD and Cosine Similarity** to optimize recommendations efficiently.

## 📊 Dataset
- The dataset contains user movie ratings from Netflix.
- There are 17770 unique movie IDs.
  There are 480189 unique user IDs.
  There are ratings. Ratings are on a five star (integral) scale from 1 to 5.
  There is a date on which the movie is watched by the user in the format YYYY-MM-DD.
- Data is structured into multiple files (`combined_data_1.txt` to `combined_data_4.txt`).
- Large-scale user interactions are processed to extract insights.

## 🛠 Technologies Used
- **Programming Language:** Python (ipython-notebook - Python Text Editor)
- **Libraries:**
  -sklearn - Machine learning library
  -seaborn, matplotlib.pyplot, - Visualization libraries
  -numpy, scipy- number python library
  -pandas - data handling library
  -XGBoost - Used for making regression models
  -Surprise - used for making recommendation system models
- **Recommendation Algorithm:** Truncated SVD (Singular Value Decomposition), Cosine Similarity

## 📈 Sample Results
Here’s an example of recommended movies for a given user:
| User ID | Recommended Movies |
|---------|------------------|
| 1001    | The Dark Knight, Inception, Interstellar |
| 1002    | Fight Club, The Matrix, Pulp Fiction |

## 📌 Future Improvements
- Implement **content-based filtering** to improve recommendations.
- Build a **Streamlit web app** for an interactive user interface.
- Optimize large-scale dataset handling with **sparse matrices**.
