# MOVIE-RECOMMENDATION-COSINE-SIMILARITY
Machine learning algorithms in recommender systems typically fit into two categories: content-based systems and collaborative filtering systems. Modern recommender systems combine both approaches.

We will be creating a content-based recommender.
# Content-Based Movie Recommendation Systems:
![image](https://user-images.githubusercontent.com/92329235/170825718-5cf76c9c-5bf8-46b9-a099-d3040840a702.png)
Content-based methods are based on the similarity of movie attributes. Using this type of recommender system, if a user watches one movie, similar movies are recommended. For example, if a user watches a comedy movie starring Adam Sandler, the system will recommend them movies in the same genre or starring the same actor, or both. With this in mind, the input for building a content-based recommender system is movie attributes.
# Tech stacks
# PYTHON : for machine learning part
# STREAMLIT: for building up a web application
# HEROKU : for deploying a web application
# tmdb3api : for showing Movie details
# cosine similarity : for showing movie recommendation
# Link to the video
CHECK OUT-> https://youtu.be/lQF9fFNJG30
# Snapshots of the application
![Screenshot (126)](https://user-images.githubusercontent.com/92329235/170825767-45890ff8-a1ec-4dd6-ab06-5d8dbabae675.png)
![Screenshot (127)](https://user-images.githubusercontent.com/92329235/170825776-29548760-48aa-4efb-9200-c68e0aef17b1.png)
![Screenshot (128)](https://user-images.githubusercontent.com/92329235/170825787-302ac11a-f248-4825-8112-72ee987c0213.png)
![Screenshot (129)](https://user-images.githubusercontent.com/92329235/170825825-d209900c-301f-4253-b2a1-1e83a469756b.png)
# How to get TMDB API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.
# RUN STREAMLIT COMMAND ON YOUR TERMINAL
the command to run the web application on your system is streamlit run appp.py
# Algorithm used for application
## Cosine similarity:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
## How does Cosine similarity works:
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
![image](https://user-images.githubusercontent.com/92329235/170826257-835b4f1b-af1e-40be-9b65-66609e1fdba9.png)
## Dataset
I have used the TMDB 5000 movies dataset to build the model
You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata
