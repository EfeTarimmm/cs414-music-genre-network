# Mapping Musical Genres as a Similarity Network Using Spotify Audio Features

## Overview

This project investigates the structural organization of musical genres using a network science approach. Musical genres are represented as nodes, and edges are created based on cosine similarity between genre-level Spotify audio feature vectors.

The project explores:

- Genre similarity networks
- Degree and betweenness centrality
- Louvain community detection
- Popularity versus structural importance
- Threshold sensitivity analysis

## Dataset

The analysis uses the Spotify Tracks Dataset containing approximately 114,000 tracks distributed across 114 musical genres.

Source:
https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

## Repository Structure

- data/ : Dataset used in the analysis
- notebooks/ : Jupyter notebook containing the full analysis pipeline
- outputs/ : Figures used in the report
- gephi/ : Network files for Gephi visualization
- report/ : Final project report (PDF and DOCX)

## Main Results

- 113 nodes
- 636 edges
- 6 Louvain communities
- Modularity = 0.61
- Weak correlation between popularity and network centrality

## Running the Project

Open:

notebooks/music_genre_network_analysis.ipynb

and run the notebook cells sequentially.

## Author

Muhsin Efe Tarım

CS414 – Network Science
Sabancı University