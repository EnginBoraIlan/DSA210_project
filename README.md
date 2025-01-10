# DSA210_project

## Motivation

Our everyday lives now revolve around social media sites like X, Instagram, and TikTok, which provide insights regarding engagement patterns and individual activity. The purpose of this project is to examine social media activity (posts and likes) in order to:
- Gain insight into everyday usage patterns across platforms.
- Determine the days and times when engagement is at its highest.
- Examine how **key time intervals** affect social media use, keeping an eye out for any behavioral changes that may occur during stressful times.
- Analyze the relationships between various platforms, such as Instagram and TikTok.
- Acquire self-awareness and knowledge about one's own social media usage patterns.

This project offers a comprehensive picture of user interaction trends by integrating data from several platforms.

---

## Data Sources

The data for this project is collected from:

1. **TikTok**:
   - Exported liked list data in `.txt` format, including the exact day and time of each liked video.

2. **Instagram**:
   - Exported activity data in `.html` format, containing timestamps of all liked posts.

All datasets are calculated daily. Due to some privacy concerns, the raw data cannot be shared.

---

## Objectives

The primary objectives of this project are:
1. To calculate and visualize the number of liked posts and videos per day on TikTok and Instagram.
2. To merge and analyze data across platforms for a comprehensive view of daily social media activity.
3. To evaluate how engagement changes during specific intervals (e.g., exam weeks) compared to regular periods.
4. To provide insights into overall social media usage patterns and trends.

---

## Methodology

### Data Collection:
- **TikTok**: Liked list data exported in `.txt` format.
- **Instagram**: Activity data exported in `.html` format.

### Data Cleaning:
- Standardized date formats across platforms to `YYYY-MM-DD`.
- Addressed any missing values and filtered irrelevant fields to focus on `Date` and `Total Likes`.

### Data Integration:
- Combined data from TikTok and Instagram for a comprehensive view of daily social media activity.
- Labeled days as either:
  - **In Interval**: Specific periods of interest (e.g., exam weeks).
  - **Out Interval**: Days outside the defined intervals.

### Exploratory Data Analysis (EDA):
- **Box Plot**: Visualized the distribution of total likes for both **In Interval** and **Out Interval** days.
- **Histogram**: Compared the frequency of likes during **In Interval** and **Out Interval** periods.
- **Scatter Plot**: Analyzed trends in daily likes over time for both intervals.

### Statistical Analysis:
- Conducted hypothesis testing to determine if the mean number of likes differs significantly between **In Interval** and **Out Interval** periods.
  - **H₀**: Means of likes during **In Interval** and **Out Interval** periods are equal.
  - **H₁**: Means of likes during **In Interval** and **Out Interval** periods are not equal.

---

## Findings

1. **Engagement Patterns**:
   - The mean number of likes during **In Interval** periods was **5.26**, with a standard deviation of **4.58**.
   - The mean number of likes during **Out Interval** periods was **9.84**, with a standard deviation of **13.32**.

2. **Hypothesis Testing**:
   - Results:
     - **T-Statistic**: -4.57
     - **P-Value**: 0.0000
     - At a significance level of 0.05, we reject the null hypothesis, indicating a significant difference between the means.

3. **Regression Analysis**:
   - Regression equations indicate trends in like counts over time:
     - **In Interval Regression Equation**: \( y = -2.13x + 40.76 \)
     - **Out Interval Regression Equation**: \( y = -1.01x + 27.54 \)
   - A sharper decline in likes was observed during **In Interval** days compared to **Out Interval** days.

4. **Visualization Insights**:
   - Boxplots revealed lower variability in likes during **In Interval** periods, indicating more consistent engagement.
   - Histograms showed a higher frequency of likes on **Out Interval** days, with greater fluctuation compared to **In Interval** days.

5. **Analysis**:
   - Exams days affects the usage rate of social media significantly.
---

## Limitations and Future Work

### Limitations:
- The dataset covers limited timeframes and may not generalize to broader contexts.
- Likes from additional platforms (e.g., X/Twitter, Facebook) were not included in this analysis.

### Future Work:
1. **Expanding the Dataset**:
   - Incorporate more diverse time periods and platforms for a comprehensive understanding of engagement trends.
2. **Including External Factors**:
   - Explore factors such as holidays, stress levels, or significant life events to better understand variations in social media engagement.
3. **Advanced Modeling**:
   - Use time-series models to predict like patterns based on past behavior.
---

## Tools and Libraries

- **Python**:
  - `pandas` for data manipulation and analysis.
  - `matplotlib` and `seaborn` for visualizations.
  - `scipy` for statistical testing.

---

Let me know if you'd like help uploading or modifying this directly in your GitHub project! 😊


