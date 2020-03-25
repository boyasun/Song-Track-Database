# Song-Track-Database
This project generate an informative database leveraging open source web APIs as well as information scraped from online. 
Song track information including song names and artist names are scraped from Billboard year-end top 100 hit song charts from year 2010 to year 2019. Using this information, we send requests to Spotify APIs to fetch quantified audio analysis features provided by Spotify including popularity scores, acousticness, danceability, liveness, etc and to MusixMatch API to get song lyrics. All data is stored in JSON format in MongoDB which is more flexible and efficient.
