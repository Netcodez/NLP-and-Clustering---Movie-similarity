# NLP-and-Clustering - Movie-similarity Analysis Project
Using NLP and Clustering on movie plot summaries from IMDB and Wikipedia to quantify movie similarity

## Introduction
This project aims to quantify the similarity between movies based on their plot summaries available on IMDb and Wikipedia, clustering them accordingly. By employing natural language processing techniques and unsupervised learning algorithms, this project clusters movies based on their plot descriptions to identify common themes and similarities among various films.
The goal is to cluster movies based on thematic similarities to better understand their relationships and groupings.

## Requirements
To run the code in this project, ensure the installation of the NLTK library using the following command:

pip -q install nltk

- Movies dataset - https://drive.google.com/file/d/1p2m41Oef8s29dkE-C_Yl9cj_DlVZiYYp/view?usp=sharing


## Workflow Overview

1. **Dataset Overview:**
   - The dataset combines plot summaries from IMDb and Wikipedia, providing a rich source of information for movie analysis.

2. **Text Processing:**
   - Text data is tokenized, stemmed using the Snowball Stemmer, and transformed into numerical representations using the TF-IDF method.

3. **Clustering with K-means:**
   - Utilizing the K-means algorithm, movies are grouped into clusters based on their genres, allowing for a comprehensive analysis of their interrelationships.

4. **Similarity Calculation:**
   - Cosine similarity is employed to measure the closeness of movie plot summaries, providing insights into their thematic similarities.

5. **Dendrogram Visualization:**
   - A dendrogram is created to visualize movie relationships, displaying hierarchical clustering results to understand the strength of similarity between various movie pairs.

### Results

- The project successfully identified five (5) thematic clusters among movies, allowing for a clearer understanding of the relationships between different films.  The dendrogram visualization showcases how movies are related based on their plot summaries.

### Usage

The provided code and analysis can be replicated in a Python environment, such as Jupyter Notebook or Google Colab, to explore movie similarities and clusters based on plot summaries.

### Conclusion

This project demonstrates how text-based movie plot summaries can be processed and clustered to reveal thematic similarities among movies. The visual representations and clustering methodologies enable a better understanding of movie relationships and thematic groupings.
