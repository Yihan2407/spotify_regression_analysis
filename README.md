# A Regression Analysis using features provided by the Spotify API to determine the most important factors that influence a track's popularity

The Spotify API allows us to view the various characteristics of each track streamed on Spotify, for example audio features such as danceability, tempo and energy, to non-audio features such as the duration of the track and whether the track contains explicit content. Finally, we have a popularity index for each track that ranges from 0 - 100, that is determined via a combination of factors, such as the total number of times the track has been streamed by users, added to users' playlists, saved to users' libraries, and also the number of times the track has been shared or listened to on social media and other platforms. As part of a final project for an introductory course to Econometrics, we conducted an exploratory data analysis as well as regression analysis on a dataset of 17,003 tracks to identify the most prominent features that can influence a track's popularity. We focused on a few variables of interest, namely danceability, instrumentalness, duration of the track, and the popularity of the artist that released the track. To account for Omitted Variable Bias, we controlled for the genre of the track and the year the track was released in. 

This finally led us to the conclusion that the popularity of the artist was likely the most important factor in influencing the popularity of a song, which possibly brings about business implications such as collaborating with more popular artists or investing more in advertising and publicity to bring about attention to an artist. Regardless, the audio features themselves have a statistically significant relationship with track popularity, although it greatly depends on the genre of the track itself. Overall, while we did not go in-depth into the regression analysis, it was a really interesting project that perhaps hinted at the possiblity of musical optimization of track characteristics that may increase a track's likability or replayability.
