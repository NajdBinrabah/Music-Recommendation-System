<h1 align="center">Music Recommendation System</h1>

<p align="center">This is a personal project focused on exploring various models for creating a Music Recommendation System</p>

---

Recommendation systems aim to suggest items to users based on their preferences and behaviour. The project explores diverse recommendation techniques, each with its unique approach to predicting user preferences. The primary goal is to understand and implement different recommendation techniques and evaluate their performance. The effectiveness of these models is evaluated using various metrics to determine the best approach for providing accurate recommendations.

You can view the detailed Notebook for this project [here](https://github.com/Najd-Binrabah/Music-Recommendation-System/blob/main/Music_Recommendation_System.ipynb). The models explored in this project include:


### 1. Popularity-Based Recommendation System:
This model provides a baseline using overall popularity metrics to recommend popular items. It is not personalized; instead, it simply recommends to a user the most popular items that the user has not previously consumed.
<br>

### 2. User-User Collaborative Filtering:
This model identifies users with similar preferences and recommends items that those users have liked. The similarity between users is typically calculated using metrics such as cosine similarity or Pearson correlation.
<br>

### 3. Item-Item Collaborative Filtering:
This approach focuses on finding items that are similar to those a user has interacted with. It recommends items that are frequently liked together with the items the user likes.
<br>

### 4. Matrix Factorization:
Matrix factorization techniques, such as Singular Value Decomposition (SVD), decompose the user-item interaction matrix into latent factors. These latent factors are used to predict missing entries in the matrix, thus providing recommendations.
<br>

### 5. Clustering-Based Recommendation System:
This model groups users into clusters based on their interaction history. Recommendations are made by suggesting items that are popular within the cluster to which the user belongs.
<br>

### 6. Content-Based Recommendation System:
Content-based systems recommend items similar to those the user has liked in the past, based on item attributes. This model relies on the features of the items to find similarities.
<br>

### 7. Ensemble Model:
The ensemble model combines the strengths of multiple recommendation techniques to provide more accurate and robust recommendations.
