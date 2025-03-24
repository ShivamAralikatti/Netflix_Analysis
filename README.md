# Netflix Data Analysis

A comprehensive analysis of Netflix content using network analysis, text mining, and trend visualization techniques.

## Overview

This project analyzes Netflix's content catalog using various data science approaches:
1. Network analysis of collaborations between directors and actors
2. Text mining of content descriptions
3. Temporal analysis of genre and rating trends

## Features

### Collaboration Network Analysis
- Constructs a network graph representing collaborations between directors and actors
- Identifies the most frequent collaborative pairs
- Calculates degree centrality to find the most connected individuals
- Performs community detection to identify clusters of frequently collaborating people
- Visualizes the network with color-coded nodes for actors and directors

### Content Description Analysis
- Processes Netflix content descriptions using natural language processing techniques
- Removes stop words and performs tokenization
- Generates word frequency analysis
- Creates visually appealing word clouds to highlight common themes

### Genre and Rating Trend Analysis
- Tracks genre distribution changes over time
- Analyzes rating trends across years
- Calculates percentage changes to identify growing genres
- Examines the correlation between genres and content ratings
- Identifies the fastest growing genres in recent years

## Requirements
-pandas
-networkx
-matplotlib
-nltk
-wordcloud
-seaborn
-python-louvain (for community detection)

## Usage

1. Download the Netflix dataset (`netflix_titles.csv`)
2. Run the network analysis script:
   python netflix_network_analysis.py

## Example Outputs

## Network Visualization
The network visualization shows connections between directors and actors, with:

-Red nodes representing directors
-Blue nodes representing actors
-Edges representing collaborations on Netflix content

## Word Cloud
The word cloud highlights the most common themes and keywords in Netflix content descriptions.

##Genre Trends
Stacked bar charts visualize how genres have evolved over time and how content ratings have changed through the years.

## Analysis Insights
The scripts generate various insights including:
-Network metrics (density, clustering coefficient)
-Community structure within the collaboration network
-Word frequency in content descriptions
-Genre growth trends
-Rating distribution changes
-Correlations between genres and ratings

## Acknowledgments
This project uses the Netflix titles dataset, which contains information about movies and TV shows available on Netflix.
