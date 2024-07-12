# Twitter Trend Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![JSON](https://img.shields.io/badge/JSON-used-brightgreen.svg)
![pandas](https://img.shields.io/badge/pandas-used-red.svg)
![matplotlib](https://img.shields.io/badge/matplotlib-used-orange.svg)

This project analyzes Twitter trends using data extracted from Twitter's API. It explores worldwide and US-specific trends, focusing on the "#WeLoveTheEarth" hashtag as a case study.

## Features

1. Load and inspect worldwide and US Twitter trends
2. Identify common trends between worldwide and US data
3. Analyze tweets related to a specific trend (#WeLoveTheEarth)
4. Extract and analyze tweet content, user names, and hashtags
5. Perform frequency analysis on names and hashtags
6. Examine tweet popularity and user influence
7. Visualize data using pandas and matplotlib
8. Analyze the distribution of languages used in tweets

## Requirements

- Python 3.x
- Libraries: json, collections, matplotlib, pandas

## Data

The project uses the following JSON files (not included in this repository):
- datasets/WWTrends.json
- datasets/USTrends.json
- datasets/WeLoveTheEarth.json

## Usage

1. Ensure all required libraries are installed.
2. Place the JSON data files in a 'datasets' folder in the project directory.
3. Run the scripts in order, following the numbered sections in the code.

## Sections

1. Thought patterns: Load and inspect worldwide and US trends
2. Making the output easy to read: Pretty-print JSON data
3. Finding common trends: Compare worldwide and US trends
4. Exploring hot trend: Analyze #WeLoveTheEarth tweets
5. Exploring further: Extract tweet text, user names, and hashtags
6. Frequency analysis: Count occurrences of names and hashtags
7. Activity around the trend: Analyze retweets and favorites
8. Data Manipulation: Create and visualize a DataFrame of tweet data
9. Analyzing used languages: Plot distribution of tweet languages

## Notes

- This project assumes you have already extracted data using Twitter's API.
- Some visualizations may require additional setup in your Python environment.

