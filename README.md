# Spotify 2020 Top 50 Track Analysis

## Overview
This project provides an analysis of the 2020 Spotify Top 50 tracks dataset, exploring various aspects of the songs, artists, albums, and features like danceability, loudness, and acousticness. It answers key questions about the dataset, such as the most popular artist, how features correlate, and how genres compare in terms of different attributes.

The analysis uses Python and can be reproduced or extended by following the setup instructions. Dependencies are managed using Poetry, which simplifies the setup of a virtual environment and installation of required packages. The project includes a Jupyter notebook to demonstrate the analysis steps and findings.

## Table of Contents
1. [Setup](#setup)
2. [Project Structure](#project-structure)
3. [Data Analysis](#data-analysis)
4. [Usage](#usage)
5. [Testing](#testing)
6. [Improvements and Future Work](#improvements-and-future-work)
7. [Contributors](#contributors)

## Setup

### Prerequisites
- Python 3.x
- Poetry for dependency management
- Jupyter Notebook (optional, for viewing the analysis)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/TuringCollegeSubmissions/eleone-DS.v3.1.3.5
   cd eleone-DS.v3.1.3.5
   ```

2. Set up a virtual environment and install dependencies using Poetry:
   ```bash
   poetry install
   ```

3. Activate the virtual environment:
   ```bash
   poetry shell
   ```

4. (Optional) If using Jupyter Notebook to view or modify the analysis:  
   ```bash
   poetry add notebook
   ```

## Project Structure
- `pyproject.toml`: Poetry configuration file listing dependencies.
- `poetry.lock`: Lock file with exact package versions.
- `spotifytoptracks.csv`: Dataset containing information about the Top 50 tracks on Spotify in 2020.
- `spotify_top50_analysis.ipynb`: Jupyter notebook with the analysis and insights derived from the dataset.

## Data Analysis

### Key Questions Answered:
1. **Dataset Overview:**
   - Total number of observations.
   - Total number of features.
   - Identification of categorical and numeric features.
2. **Artists & Albums:**
   - Artists with multiple popular tracks.
   - Most popular artist.
   - Total number of artists.
   - Albums with multiple popular tracks.
   - Total number of albums.
3. **Track Characteristics:**
   - Tracks with high/low danceability.
   - Tracks with high/low loudness.
   - Longest and shortest tracks.
4. **Genre Analysis:**
   - Most popular genre.
   - Genres with single popular tracks.
   - Total number of represented genres.
5. **Feature Correlations:**
   - Strong positive/negative correlations.
   - Features that are not correlated.
6. **Comparative Analysis:**
   - Danceability, loudness, and acousticness comparisons between Pop, Hip-Hop/Rap, Dance/Electronic, and Alternative/Indie genres.

## Usage

### Running the Jupyter Notebook
To interact with the data analysis or run your own queries, use the Jupyter notebook:
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook spotify_top50_analysis.ipynb
   ```
2. Follow the cells to explore the analysis, or modify them to perform your own exploration.

## Testing
Although no explicit unit tests are provided in this project, users can validate the dependencies and their environment setup using:
```bash
poetry check
```

## Improvements and Future Work
- **Comparative Analysis:** Comparing this dataset to the Top 50 tracks from 2019 or 2021 could reveal trends in genre popularity, helping to identify which genres are becoming more prominent or declining in relevance. Additionally, examining how specific attributes like danceability correlate with these genres could provide deeper insights.

- **Data Visualization:** Implementing data visualization techniques would enhance the representation of correlations between various features, allowing for quicker identification of patterns and trends in the dataset.

- **Lyric Analysis:** If feasible, obtaining the lyrics for each song would enable an analysis of the relationship between lyrical content and popularity. This could uncover whether songs with more or fewer lyrics tend to rank higher, and it may reveal trends regarding instrumental tracks.

- **Cross-Platform Comparison:** Comparing this dataset with similar datasets from other platforms, such as SoundCloud or YouTube Music, could help assess whether there are significant differences in music preferences among users of different streaming services.

## Contributors
- [Erikas Leonenka](https://github.com/eleonen)
