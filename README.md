# spotify-trends
The final project for IST 421: Data Visualization, using R and Adobe Illustrator

# Sound of the Times: Decoding Two Decades of Emotional Shifts in Music

**Ava Langanki | IST 421: Information Visualization | Fall 2024**

**[View the final poster (PDF)](langanki-421-final.pdf)**

## Overview

This project looks at what popular music from 2000 to 2019 says about society's collective emotional state. Using Spotify's top hits, I analyzed how genre, energy, and musical positivity (valence) shifted over two decades, and designed a poster that presents the story visually.

## Research Questions

1. How have genres, energy, and mood shifted over the past 20 years?
2. What characteristics make certain songs particularly popular over the past 20 years?
3. How does musical positivity reflect changes in society over time?

## Data

- **Source:** [Top Hits Spotify from 2000-2019 (Kaggle)](https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019)
- **Size:** 1,879 tracks, 18 columns (artist, title, tempo, key, danceability, energy, valence, popularity, explicit, genre, and more)
- **Preparation:** Removed null values, simplified multi-genre tags into one main genre per track, and aggregated audio features by year and genre

## Visualizations

The poster includes 7 visualizations built in R:

| Visualization | Purpose |
|---|---|
| Average energy and valence by year (line chart) | Main trend across 2000 to 2019 |
| Energy vs. valence by genre (bubble chart) | Compares genre mood, sized by number of songs |
| Explicit vs. non-explicit songs by decade (pie charts) | Shift in explicit content |
| Top genres by popularity (bar chart) | Which genres score highest on average |
| Song duration by genre (box plot) | Length differences across genres |
| Tempo distribution by genre (density plot) | Tempo patterns across genres |
| Danceability vs. energy (scatter plot) | Relationship between two audio features |

## Key Findings

- **Positivity declined.** Average valence fell from about 0.65 in 2001 to about 0.46 in 2018, before a small rebound in 2019.
- **Energy peaked, then dropped.** Average energy was highest around 2010 to 2012 and reached its low in 2018, then spiked in 2019.
- **Explicit content grew.** Explicit tracks rose from 26.8% of hits in 2000-2009 to 29.9% in 2010-2019.
- **Genres differ in mood.** Country had the highest average valence, while Folk/Acoustic had the lowest energy and valence.

## Tools

- **R:** tidyverse (dplyr, ggplot2) for cleaning, analysis, and charts
- **Adobe Illustrator:** poster layout and design

## Files

| File | Description |
|---|---|
| `langanki-421-final.pdf` | Final project poster |
