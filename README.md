IN THE WORKS (WIP)
❓ Question: how can we recommend podcasts to a user who likes a certain content influencer or podcast?

🗃️ Datasets: https://www.kaggle.com/datasets/roman6335/13000-itunes-podcasts-april-2018?resource=download

🛠️ Method: Built a Content-Based Filtering algorithm, inspired by Netflix which personalizes recommendations for each user based on the content they interact with.
Created a similarity score using pairwise cosine similarity of XYZ. It uses the TF-IDF algorithm to create vector representations of podcast descriptions and calculates cosine similarity between these vectors to find similar podcasts.
Assembled podcasts and scores in a dataframe containing all unique pairs of podcasts in the sample and visualize the relationships in a graph model using node.js
