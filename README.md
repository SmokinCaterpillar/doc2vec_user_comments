# Analysis of Online User comments with gensim Doc2Vec

Doc2Vec is a nice neural network framework for text analysis. The machine learning technique computes so called document and word embeddings, i.e. vector representations of documents and words. These representations can be used to uncover semantic relations. For instance, Doc2Vec may learn that the word "King" is similar to "Queen" but less so to "Database".

I used the Doc2Vec framework to analyze user comments on German online news articles from SPON, ZEIT, and Focus and uncovered some interesting relations among the data. Furthermore, I fed the resulting Doc2Vec document embeddings as inputs to a supervised machine learning classifier. Accordingly, given a particular comment, can we determine from which news site it originated? Are there patterns among user comments? Can we identify stereotypical comments for different news sites?

You can find a Jupyter Notebook abut the Doc2Vec and ML models in this repository. Unfortunately, I cannot provide the raw scraped user comment data (yet), because I am lacking permissions by the publishers.

I gave a presentation about this project at the PyData conference. The slides can be found in this repository and you may [watch the talk on YouTube](https://www.youtube.com/watch?v=zFScws0mb7M).
