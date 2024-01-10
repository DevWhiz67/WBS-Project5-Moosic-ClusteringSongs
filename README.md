# WBS-Project5-Moosic-ClusteringSongs
## Using unsupervised machine learning (K-means) to cluster songs

Moosic is a little start-up that creates playlists curated by music experts and specialists in old and new trends. Users can subscribe to their website and listen to these playlists through their preferred Music App (be it Spotify, Apple Music, Youtube Music…). They love the fact that their playlists have a personal touch, and that each playlist encapsulates a certain “mood” or “style”. But business is scaling up fast and the music experts are slow in creating new playlists. 

Therefore our task was to use machine learning to add a degree of automatisation to the creation of playlists. The dataset provided has been collected from the Spotify API and contains several audio features (tempo, energy, danceability…).

Our project had three main parts:

- Data preparation:
    - Reading the data
    - Initial quick exploration
    - Dropping unwanted features
- Modelling:
    - Data scaling (potentially, other transformations)
    - K-Means exploration of clusters (elbow method, silhouette coefficient…)
    - K-Means final model
- Cluster exploration:
    -Univariate , bivariate, and multivariate exploration of the clusters
    - Manual labelling of the clusters
