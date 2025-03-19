# BHMLAI_Capstone1: Music Recommendation System

### Research Question:

Most song recommendation system proposes next track based on popularity and number of hits on the song track. However, there could be some song tracks that couldn't gain popularity so far but align with the features of song being liked by the listener.

## Technique:

KMeans and DBScan model comparison are used for this purpose with KMeans model applied to achieve expected result.

## Expected Result:

Based on the analysis, the algorithm calculates the probability of each song being the next selection and presents the most likely options as recommendations.

## Why this question is important:

Song track based on popularity and favorite artist are commonly recommended as next track. During this process of recommendation, many song tracks old or new may not be presented as next recommendation even if there features align with the current song being played by listener. Those melodic and unheard tracks could be predicted using this algorithm purely based on common features of dataset and not only based on popularity or top hits of the tracks. Listener can experience new blend of music and opportunity arises for new upcoming artist for their talent.

### Data Description:

- Dataset: https://www.kaggle.com/datasets/maxkuz/spotify-electronic-music-datasetLinks to an external site.
- Dataset includes 57460 rows and 50 features.
- There are no nulls in the dataset.
- There are no duplicates in the dataset.
- Important features used are:
  - track_name
  - artists_names
  - danceability
  - energy
  - key
  - loudness
  - mode
  - speechiness
  - acousticness
  - instrumentalness
  - liveness
  - valence
  - tempo
  - album_name
  - genres
  - artist_name
- Target feature is track_name

### Summary of Findings
- KMeans model performed very well on the dataset to produce actual results compared to expected output.
- Frequent training and modeling may produce better result with optimal resources to compute data.
- KMeans can efficiently handle large datasets due to its linear time complexity.
- TensorFlow and GNN deep learning could also be used for this purpose.
- A more balanced dataset could have been better.
- Downside is it only worked for numerical data.
- KMeans assumes that clusters are roughly the same size, which is not always the case.

### Project URL
- GIT: https://github.com/sugandhpurohit/BHMLAI_Capstone1

### Few screenshots from project

![KMeans Vs DBScan Scores](https://github.com/user-attachments/assets/5243c624-ba52-4c9d-847c-2376c11ef6b3)

![KMeans Clustering](https://github.com/user-attachments/assets/cbd00567-6353-4af8-ba70-7232b7e8295c)

![Identified Points of Similar Tracks](https://github.com/user-attachments/assets/289be7f3-e790-4db7-9ea4-c6dac1d892f8)




