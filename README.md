<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# SONG RECOMMENDER 3000
Pol Serramalera

Data Analytics full time 09/nov/2020

## Content
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Links](#links)


## Project Description
This project seeks to create a program that returns a random song froma 10000 song cluster based on the audiofeatures of the song inputed by a user. The program will return the song and artist of a similar song in terms of acousticness, danceability, keys, tempo etc.


## Dataset
Created on the code:

·billboard.csv
·final_playlist.csv

## Workflow

1. First I have done a little of webscrapping in order to get the billboard top 100 hot songs from the billboard website
2. Then definining a function to convert any spotify playlist into a datafram with the audiofeatures of eachsong of the playlist
3. With the function defined, extract audio fetures of 10000 songs
4. Clustering the dataframe with kmeans
5. Defining the loop function so the user can easily input a song and get a recommendation back

## Links  
[Video presentation](https://drive.google.com/file/d/1KQPqwgiSVdG6qKZaUzcGv_tCApZOORp3/view?usp=sharing)  

