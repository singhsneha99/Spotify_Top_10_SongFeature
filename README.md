# Spotify Wrapped Top Track Analysis

This repo contains code to fetch your Spotify Wrapped top tracks and analyze their audio features using the Spotify API and Python.

## Overview

The Jupyter notebook `music.ipynb` demonstrates how to:

- Set up authentication with the Spotify API
- Get a user's top tracks for a time period 
- Retrieve audio feature data on those tracks
- Analyze features like danceability, energy, acousticness etc.
- Visualize the audio features for comparison

This enables you to go beyond just a list of your top tracks and gain insights into your listening habits and music taste based on track audio characteristics.

## Usage

1. Clone this repo 
2. Obtain your Spotify developer credentials (Client ID & Client Secret)
3. Add your credentials and Spotify username to the notebook
4. Run the notebook cells to fetch your data and generate visualizations

## Requirements

- Python 3
- Spotipy library 
- Pandas, Matplotlib, NumPy

## Output

The output includes dataframes of your top tracks and their audio features, as well as radar charts visualizing the feature differences across your top songs.

## References

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [Spotipy Documentation](https://spotipy.readthedocs.io/)
