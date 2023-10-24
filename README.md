# Spotify: Higher or Lower
'requires flask and flask_session and spotipy and numpy'

>88Motivation:** Introducing interactive music artist popularity comparison games, similar to HigherLower, fills a niche in the entertainment/music industry and helps users diversify their music horizons. These games engage users through immersive experiences, leveraging data-driven approaches through a simple and fun game.


>**Problem:** The problem our group intended to solve is the lack of innovative ways to connect users to new music. We aim to tackle an entertainment challenge revolving around music, specifically with the approach of engaging users through a comparison of artists and their popularity. Music artist popularity comparisons offer a unique and interactive way to enhance the user experience by leveraging the inherent human tendency to evaluate and rank.

>**Features Implemented:** With the implementation of the Spotify API’s data on artists, we generated thousands of data points of artists and columns such as related artists, genre, and popularity which are then stored in a JSON. The quicksort and mergesort algorithms are implemented so that more popular artists are sorted to the front to allow for increasing difficulty as the user progresses. A unique game user interface that shows the current artist and two related artists that the user must choose from. A composite similarity score calculation uses cosine similarity to features such as genres, related artists, popularity, and playlist cooccurrence to find a similarity value between two artists.

>**Reflection:** I gained proficiency in utilizing the Spotify API to facilitate the implementation of sorting algorithms. To extract and sort the required data, I familiarized myself with the SpotiPy library. I also learned about the limitations of the Spotify API compared to other music streaming APIs. For example, it does not support the creation of new playlists or modification of playlists.

## Tools/Languages/APIs/Libraries Used
* Python
* HTML/CSS
* JavaScript
* SpotiPy
* NumPy
* Flask
* Spotify API

## Documentation
https://docs.google.com/document/d/1WuitLVCgzWC9zF1uKObtwHBR64Z0OUN406yUvL74kPw/edit#
