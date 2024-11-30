# DSA210_project

# TikTok, Instagram, and X Likes Analysis

## Motivation
   Our everyday lives now revolve around social media sites like X, Instagram, and TikTok, which provide insights regarding engagement patterns and individual activity. The purpose of this project is to examine social media activity (posts and likes) in order to: 
   - Gain insight into everyday usage patterns across platforms.
   -Determine the days and times when engagement is at its highest.
   -Examine how **exam weeks** affect social media use, keeping an eye out for any behavioral changes that may occur during stressful times.
   -Analyze the relationships between various platforms, such as Instagram and TikTok.
   -Acquire self-awareness and knowledge about one's own social media usage patterns.

This project offers a comprehensive picture of user interaction trends by integrating data from several platforms.

## Data Sources

The data for this project is collected from:

1. **TikTok**: 
   - Exported liked list data that includes liked videos with the right day and time in a `.txt` format.

2. **Instagram**:
   - Exported personal activity data in an `.html` format.
   - Includes timestamps of all liked posts.

3. **X**:
   - Also exported personal activity data that includes all of the past activites and total usage in an `.html` format.

All datasets are calculated daily. Due to some privacy concerns data cannot be shared.

## Objectives
The primary objectives of this project are:
1. To calculate and visualize the number of liked posts and videos per day on TikTok, Instagram, and X.
2. To merge and analyze data across platforms for a comprehensive view of daily social media activity.
3. To evaluate how engagement changes during exam weeks compared to regular periods.
4. To provide insights into overall social media usage patterns and trends.

## Tools and Methods
- **Python**
- **Libraries**: 
  - `pandas` for data manipulation and analysis.
  - `matplotlib` for visualizations.
  - `BeautifulSoup` for parsing HTML files (Instagram data).
