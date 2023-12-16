# YouTube Channel Analysis

This project involves conducting a data analysis on YouTube channels using Python. The analysis includes retrieving channel statistics, fetching video details, and performing various data manipulations and visualizations for comprehensive insights. The project utilizes the YouTube API for data retrieval and pandas for data manipulation, along with seaborn and matplotlib for visualization.

## Prerequisites
- Ensure you have a valid YouTube API key. You can obtain one [here](https://developers.google.com/youtube/registering_an_application).

## Code Explanation

### Fetching Channel Statistics
- The `fetch_channel_stats` function retrieves channel statistics for the specified channel IDs using the YouTube API.
- The result is displayed as a DataFrame containing channel information.

### Fetching Video IDs
- The `fetch_video_ids` function retrieves video IDs from the specified playlist using the YouTube API.
- The result is a list of video IDs.

### Fetching Video Details
- The `fetch_video_details` function retrieves detailed information for each video using the YouTube API.
- The result is displayed as a DataFrame containing video information.

### Data Manipulation
- Conversion of count columns (`viewCount`, `likeCount`, `commentCount`) to numeric format.
- Extraction of publish day and conversion of video duration to seconds.

### Data Visualization
- Displaying the top-performing videos using a bar plot.
- Visualizing the distribution of views per video using a violin plot.
- Generating a word cloud for video titles.

### Upload Schedule
- Analyzing the upload schedule by creating a bar plot of the number of videos published on each day of the week.

## Usage
1. Replace the `api_key` variable with your YouTube API key.
2. Modify the `channel_ids` variable to include the desired YouTube channel IDs.

## Acknowledgments
- [YouTube API Documentation](https://developers.google.com/youtube/v3)
- [WordCloud Documentation](https://github.com/amueller/word_cloud)
