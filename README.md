# EXPLORATORY DATA ANALYSIS OF A SPOTIFY USER
Spotify is one of the most used platforms for streaming music and podcasts in today's age. It is a a freemium service, the basic features being free with advertisements and limited control, while the paid subscription  has offline listening, ad-free.[wikipedia](https://en.wikipedia.org/wiki/Spotify)

In this dataset, we take a look at a user's history of their spotify account. Through EDA, we hope to identify the user's listening behaviour.

## Data Understanding
The data was taken from [kaggle](https://www.kaggle.com/datasets/anandshaw2001/top-spotify-songs-in-countries?select=spotify_history.csv). The following is a brief description of its columns:
- `spotify_track_uri` - Identifies each track
- `ts` - Timestamp indicating when the track stopped playing in UTC
- `platform` - Platform used when streaming the track.
- `ms_played` - Number of millisecond the stream was played.
- `track_name` - Name of the track.
- `artist_name` - Name of the artist.
- `album_name` - Name of the album.
- `reason_start` - Why the tracjk started.
- `reason_end` - Why the track ended.
- `shuffle` - True of False depending on if suffle mode was used when playing the track.
- `skipped` - True or False depending on if the user skipped to the next song.

## Objectives
1. Who are the most listened artists?
2. Which platform does the user use most?
3. Which year/month did he spend most time listening?

## EDA
### Most played artists
<img width="797" height="701" alt="image" src="https://github.com/user-attachments/assets/f17ecb87-8b25-427e-8a59-c03822f232ac" />

### Platforms used
<img width="597" height="519" alt="image" src="https://github.com/user-attachments/assets/c125187a-f318-424f-9501-56efd69ce8ca" />

### Most played months by year
<img width="1001" height="584" alt="image" src="https://github.com/user-attachments/assets/6e4541e4-703f-4139-9e1c-ff4556179d6b" />

### Shuffle or no shuffle
<img width="597" height="475" alt="image" src="https://github.com/user-attachments/assets/09da95ad-6575-4146-8d11-865da6b574cd" />

## Conclusion
1. From the graphs, it can be seen that the user listens mostly to rock and pop based on the artists that get more playing time.

2. It is also observed that the user used an android device most. This can be assumed to be their phone.

3. The user streamed alot in 2020. This can be attributed to lockdown period, where people spent most of their time in the house.

4. The user doesn't skip most of his tracks and uses shuffle often. Most songs are played to the end, suggesting they like the song, or they've created playlist(s) of songs they like.

