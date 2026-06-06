Spotify Data Analysis Project
Author: Urvesh Dabhi
Project Overview
This project analyzes Spotify track data to uncover insights related to song popularity, genres, artists, and audio features such as danceability, energy, and valence.
Dataset
	•	Source: Kaggle Spotify Tracks Dataset
	•	113,549 track-genre records
	•	89,740 unique tracks
	•	21 features
Tools Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Jupyter Notebook
Data Cleaning
	•	Removed missing values
	•	Removed duplicate rows
	•	Created a duration_min feature
	•	Investigated duplicate track IDs caused by multi-genre track entries
Key Findings
	1	The Top 100 most popular tracks are distributed across many artist entries rather than a small group of artists.
	2	Pop-film and K-pop have the highest average popularity among genres.
	3	Popular songs are significantly more danceable than the average song.
	4	Popular songs are only slightly more energetic than average songs.
	5	Positive and negative songs have similar popularity levels.
	6	Negative songs slightly outnumber positive songs in the dataset.
Limitations
	•	Collaborative tracks are treated as combined artist entries.
	•	Some tracks appear across multiple genres.
	•	Spotify popularity is a platform-specific metric and not a direct stream count.
Files
	•	spotify_project.ipynb — Complete analysis notebook
	•	spotify.csv — Dataset used for analysis
