# Spotify-Streaming-History
Spotify user's complete music streaming history data, including timestamps, track, artist, and album names, and reasons for playing and ending each track.
# Data Preparation/ Transformation
I used Power Query to clean and transform the data before analysis. Some key steps taken include:
- Changed data types to appropriate data types for the various columns.
- Trimmed and Cleaned text columns to remove any trailing/leading spaces.
- Removed Duplicates.
- Blanks in reason song starts and ends columns constituted & lt; 1%. Instead of being removed, blanks were replaced with "Unknown".
# key steps were taken in Power BI Desktop:
- Created a one-to-many relationship between the date table and Spotify history table using the date as the primary key.
- Created a table for calculated measures to ensure proper organization.
# Dashboard Design
- Total minutes streamed on overview page represents total listening time from 2013 to 2024.
- The heatmap uses a gradient where lighter shade of green highlights the highest values, gradually fading into black for the lowest ones.
## Definition of some metrics:
- Total Streams: Number of times a song is streamed or played.
- Total Minutes: Amount of time spent listening to songs in minutes.
- Shuffle Usage: The rate at which the Spotify user listens to songs on shuffle mode.
# Insights
- The user is a big fan of pop music, as artists such as The Beatles, The Killers and John Mayer were the user's favourites.
- Ups and downs in listening activity are observed over the years with noticeable spikes observed normally during the 3rd and 4th quarters of every year. This may signal a possible increase in entertainment as the holidays approach.
- Total Album 12.2k, and Total artist 844, Music played 2bn.
- 63.17% of streams were on shuffle mode showing a clear preference for a diverse playback.
- Android made up 75% of streams with Cast to Device comprising the least. This may signify a strong patronage of Spotify by android users as IOS users(the next highest) may be accustomed to apple music.
Generally, the user enjoys variety, nostalgia, and listening during downtime. They prefer shuffle mode, enjoy classics from The Beatles and is most probably an android user.
