This is a challenge to predict the search relevance of search results on homedepot.com. More than 73% of the products in the dataset were unique items, which presented a challenge in training the model. This dataset required text cleaning and feature extraction.

I used natural language processing (NLTK) to derive the word stems on the product title, description and search terms. I then created features based on cosine distance, shared words, Edit distances, Search query length of the product title and description. Used sckit-learn models to predict the Relevance scores. Models were evaluated based on the RMSE.

