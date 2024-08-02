# Spotify-Top-Songs-2023
**Most Streamed Spotify Songs In 2023**

As part of my journey to mastering Power BI, I wanted to take on a project to apply what I have learned so far, to a dataset related to the most popular tracks streamed on Spotify in 2023.

Check out my full Power BI report for a better experience and readability

Below is a summary of the steps involved in creating the two reports

## Tasks Overview
There are two tasks involved, both of which I will make a dashboard for:

### Task #1: Generating an Overview Report
Creating insights about the different metrics within the dataset to find out how they interact with each other, as well as some basic comparative information.

### Task #2: Drill Down to a Successful Track/Artist
Focusing on a successful track/artist to study its/their success.

### Source
[Most Streamed Spotify Songs 2023](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data)

I have filtered the dataset to get only the relevant columns:

## Dataset Columns and Descriptions

1. **`track_name`**: The name of the track/song.
2. **`artist(s)_name`**: The name(s) of the artist(s) who performed the track. Multiple artists are separated by commas.
3. **`artist_count`**: The number of artists featured on the track.
4. **`released_year`**: The year the track was released.
5. **`released_month`**: The month the track was released.
6. **`released_day`**: The day of the month the track was released.
7. **`in_spotify_playlists`**: The number of Spotify playlists that include the track.
8. **`in_spotify_charts`**: The number of times the track has appeared in Spotify charts.
9. **`streams`**: The total number of streams the track has accumulated.
10. **`bpm`**: The beats per minute of the track, indicating its tempo.
11. **`danceability_%`**: A measure of how suitable a track is for dancing, ranging from 0% to 100%.
12. **`valence_%`**: A measure of the musical positiveness conveyed by the track, ranging from 0% (sad, depressed) to 100% (happy, cheerful).
13. **`energy_%`**: A measure of the intensity and activity of the track, ranging from 0% to 100%.
14. **`acousticness_%`**: A measure of how acoustic the track is, ranging from 0% to 100%.
15. **`instrumentalness_%`**: A measure of the likelihood that the track is instrumental, ranging from 0% to 100%.
16. **`liveness_%`**: A measure of the presence of a live audience in the recording, ranging from 0% to 100%.
17. **`speechiness_%`**: A measure of the presence of spoken words in the track, ranging from 0% to 100%.

---

## Task #1: Overview Report

![image](https://github.com/user-attachments/assets/1b792116-302d-4c35-bb0f-f37b8d0611ca)


### Insights

1. **Total Streams**: Amount to an impressive total of **486 billion streams**, indicating a high level of engagement and popularity for the tracks featured.
2. **Average Streams per Track**: On average, each popular track has **516 million streams**.
3. **Top Performing Track**: "Blinding Lights" by The Weeknd, with roughly **3.7 billion streams**. This figure is about 6.7x that of the average streams per track.
4. **Top Performing Artist**: Taylor Swift, with a total of **14 billion streams**, making her the most successful artist in the history of Spotify.
5. **Top Tracks by Number of Shazams**: "Makeba" leads, followed by "Daylight" and tracks from the Barbie soundtrack. This indicates which tracks are not only popular but also frequently searched for by listeners.
6. **Distribution of Artist Groups**: 
   - 39.3% of tracks are performed by solo artists.
   - 34.3% of tracks are performed by duos.
   - The remaining percentages represent tracks with more than two artists, with smaller percentages for larger groups.
   - Solo and duo artists are the most common performance features in the dataset.
7. **Relationship Between Song Energy and Danceability**: Shows a positive relationship between energy and danceability. Tracks with higher energy levels tend to have higher danceability scores, indicating that more energetic tracks are generally better suited for dancing.
8. **Total Tracks Released by Month**: Displays the number of tracks released each month. There are noticeable peaks and troughs:
   - A peak in May indicates a high number of releases.
   - A significant drop in July suggests fewer releases.
   - This could be useful for identifying trends in music releases over time.

---

## Task #2: Detailed Analysis of The Weeknd

![The Weeknd Overview](https://github.com/user-attachments/assets/f1a17855-d2bd-49ac-a9f9-e042c55cecb8)

![image](https://github.com/user-attachments/assets/8845d2f4-6719-4850-9e82-c2b71f1ec737)


### Insights

1. **Monthly Streams**: The Weeknd rakes in almost **2 billion streams** monthly.
2. **Times Added to Playlists**: Shows the number of times his songs have been added to playlists by Spotify users.
3. **Chart Appearances**: Showcases the number of times the artist's songs have made an appearance in Spotify's top charts.
4. **Top Tracks by Total Streams and Energy (%)**: 
   - "Blinding Lights" not only tops the list of most streamed tracks but also shows a balance of high energy, making it suitable for a wide range of listeners and settings.
   - Another track, "Starboy," also appears in the top 10, further solidifying his position as a leading artist with multiple high-performing songs.
5. **Song Dance-Ability % vs. Others**: The Weeknd's songs have a higher average danceability percentage (**71%**) compared to others (**64%**), which means his tracks are generally more suitable for dancing.
6. **Song Acousticness % vs. Others**: His songs have a higher average acousticness percentage (**36%**) compared to others (**35%**). It explains that his tracks tend to be more acoustic than the average track.
7. **Top 5 Artists by Most Tracks Released**: The Weeknd is named in **21 tracks** that belong to the top charts, indicating his constant presence in the music industry. This steady performance is one of the many factors that keeps him relevant in the public eye and the music industry.
8. **Top 5 Solo Artists by Total Streams**: He has accumulated **13.8 billion total streams** in his solo ventures, placing him among the top solo artists and demonstrating his talent for not needing any other feature artists.

---
