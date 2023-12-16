# 📺 YouTube Channel Analysis 📊

Analyze YouTube channels with Python 🐍! This project uses the YouTube API, pandas, seaborn, and matplotlib for data manipulation and visualization.

## Prerequisites
- Get your YouTube API key [here](https://developers.google.com/youtube/registering_an_application).

## Code Overview

### Fetching Channel Stats 📈
- Use `fetch_channel_stats` to get channel info.
- Result: DataFrame with channel data.

### Fetching Video IDs 🎥
- Use `fetch_video_ids` for video IDs.
- Result: List of video IDs.

### Fetching Video Details 📹
- Use `fetch_video_details` for detailed video info.
- Result: DataFrame with video data.

### Data Manipulation 🔄
- Convert count columns to numeric.
- Extract publish day & convert duration to seconds.

### Data Visualization 📉
- Display top videos with a bar plot.
- Visualize views distribution with a violin plot.
- Generate a word cloud for video titles.

### Upload Schedule 🗓️
- Analyze upload schedule with a bar plot.

## Usage
1. Replace `api_key` with your YouTube API key.
2. Modify `channel_ids` with your desired channel IDs.

## Acknowledgments 🙌
- [YouTube API Documentation](https://developers.google.com/youtube/v3)
- [WordCloud Documentation](https://github.com/amueller/word_cloud)

Enjoy exploring YouTube channel insights! 🚀
