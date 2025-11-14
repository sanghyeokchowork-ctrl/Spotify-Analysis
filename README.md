# 🎵 Spotify "Dark R&B" Artist & Track Analysis

This project uses the Spotify API and the `spotipy` library to collect and analyze data for a curated list of 14 artists, primarily in the 'Dark R&B' and 'Trap Soul' sub-genres.

The primary goal is to build two key datasets:
1.  **Artist Context:** Artist-level data including popularity, followers, and genres.
2.  **Track Features:** Song-level data including the Top 10 tracks for each artist and their detailed audio features (e.g., danceability, energy, valence) to analyze factors contributing to song popularity.

## 📊 Data Collected

### 1. Artist Context Data (`feature_list`)
* Artist Name & ID
* Artist Popularity (0-100 score)
* Follower Count
* Genre Tags (e.g., `'dark r&b'`, `'trap soul'`)
* Album Count

### 2. Track Feature Data (`df`)
* Track Name & ID
* Track Popularity (0-100 score)
* Artist Name & Popularity (for context)
* Audio Features:
    * `danceability`
    * `energy`
    * `acousticness`
    * `instrumentalness`
    * `liveness`
    * `loudness`
    * `speechiness`
    * `valence`
    * `tempo`
    * `key` & `mode`

## 🛠️ Technologies Used

* Python 3.9.6
* Jupyter Notebook (`.ipynb`)
* **Spotipy:** The main Python library for the Spotify API.
* **Pandas:** For creating and analyzing the final `DataFrame`.
