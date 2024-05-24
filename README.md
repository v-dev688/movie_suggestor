# Project: Movie Suggestion system!

<img src="demo/6.jpeg" alt="workflow" width="70%">


### Content Based :


A content-based recommendation system is a filtering method used to predict a user's preferences by analyzing the attributes of items they have previously interacted with and liked. Unlike collaborative filtering, which relies on user interactions and similarities between users, content-based systems focus on the characteristics of items themselves. For instance, in a movie recommendation system, the algorithm considers features such as genre, director, actors, and plot keywords. It then matches these features to the user’s past preferences to suggest new items with similar attributes. This approach leverages techniques from information retrieval and machine learning, including natural language processing to analyze textual data. Content-based recommendations are particularly useful in scenarios where user interaction data is sparse, ensuring personalized suggestions based on the intrinsic properties of items. The primary advantage of content-based systems is their ability to recommend items without requiring extensive user data, thus mitigating the cold start problem for new users and items. However, they may suffer from limited diversity in recommendations, often suggesting items that are too similar to those already known to the user, and they require extensive feature engineering to accurately represent the content attributes


# Demo:

<img src="demo/1.png" alt="workflow" width="70%">

<img src="demo/2.png" alt="workflow" width="70%">

<img src="demo/3.png" alt="workflow" width="70%">


# Dataset has been used:

* [Dataset link](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

# Concept used to build the model.pkl file : cosine_similarity

1 . Cosine Similarity is a metric that allows you to measure the similarity of the documents.

2 . In order to demonstrate cosine similarity function we need vectors. Here vectors are numpy array.

3 . Finally, Once we have vectors, We can call cosine_similarity() by passing both vectors. It will calculate the cosine similarity between these two.

4 . It will be a value between [0,1]. If it is 0 then both vectors are complete different. But in the place of that if it is 1, It will be completely similar.

5 . For more details , check URL : https://www.learndatasci.com/glossary/cosine-similarity/

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/entbappy/Movie-Recommender-System-Using-Machine-Learning.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movie python=3.7.10 -y
```

```bash
conda activate movie
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```

Now run,
```bash
streamlit run app.py
```

