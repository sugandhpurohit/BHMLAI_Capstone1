# BHMLAI_Capstone1

### Research Question:

Most song recommendation system proposes next track based on popularity and number of hits on the song track. However, there could be some song tracks that couldn't gain popularity so far but align with the features of song being liked by the listener.

### Data:

https://www.kaggle.com/datasets/maxkuz/spotify-electronic-music-datasetLinks to an external site.

## Technique:

Neural networks: Complex models that can learn non-linear relationships between features and potential next songs, often used for more sophisticated predictions.

## Expected Result:

Based on the analysis, the algorithm calculates the probability of each song being the next selection and presents the most likely options as recommendations.

## Why this question is important:

Song track based on popularity and favorite artist are commonly recommended as next track. During this process of recommendation, many song tracks old or new may not be presented as next recommendation even if there features align with the current song being played by listener. Those melodic and unheard tracks could be predicted using this algorithm purely based on common features of dataset and not only based on popularity or top hits of the tracks. Listener can experience new blend of music and opportunity arises for new upcoming artist for their talent.

## EDA
- Dataset includes 57460 rows and 50 features.
- There are no nulls in the dataset.
- There are no duplicates in the dataset.
- Some of the features can be removed from the dataset that doesn't hold much relevance to objective of the task like:
['track_id', 'track_number', 'artists_ids', 'album_id', 'main_artist_id', 
                      'album_release_date', 'total_tracks', 'type', 'image_url', 'album_label', 
                      'born_or_founded_in', 'positions_and_years_data', 'artists_count', 'album_name_length',
                      'track_name_length', 'cover_id', 'followers', 'album_popularity', 'available_markets',
                      'main_artist_name_length', 'available_markets_count', 'duration_sec', 'time_signature', 
                      'artist_popularity', 'lowest position', 'mean_position', 'position_std', 'best_position', 
                      'times_in_rating', 'dj_score', 'release_year', 'release_month'])

- Target Feature is 'track_name'.
- Important features that may show correlation with targe feature are :
['track_name', 'track_popularity', 'explicit', 'artists_names',
       'danceability', 'energy', 'key', 'loudness', 'mode', 'speechiness',
       'acousticness', 'instrumentalness', 'liveness', 'valence', 'tempo',
       'album_name', 'genres', 'artist_name']

### Summary of Findings
TBD

### Project URL
- GIT: https://github.com/sugandhpurohit/BHMLAI_Capstone1
