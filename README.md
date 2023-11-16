## Data Analysis of My Favorite YouTubers using YouTube API

### Introduction

Explore the world of YouTube through data analysis of some of my favorite YouTube creators! This project utilizes the YouTube API to delve into the metrics of channels such as Data with mo, Matt Mike, Luke Barousse, Ken Lee, and Alex the Analyst. The goal is to uncover interesting patterns, measure audience engagement, and gain insights into what makes their content popular.

You can view my work over here: <a href="https://github.com/Swapppyy/Data-Analysis-on-my-Favorite-Youtubers/blob/main/Analysis%20on%20Favorite%20Youtubers.ipynb" target="_blank"><code>My Jupyter Notebook</code></a>

### Aim and Objectives

#### Understanding the YouTube API

Learn how to use the YouTube API to gather information about videos.

#### Investigating YouTube Video Success Factors

Explore common beliefs about successful YouTube videos, including:
- Does having more likes and comments lead to more views?
- Is the length of a video important for getting views and interactions?
- Does the length of the video title affect views?
- How many tags do well-performing videos usually have, and what tags are common?

#### Analyzing Creator Upload Patterns

Examine the upload frequency of the creators. How often do they post new videos, and on which days of the week?

### Steps of the Project

**Obtain Video Metadata via YouTube API**
   - Create a developer key.
   - Request data and transform the responses into a usable data format.

**Preprocess Data and Engineer Additional Features for Analysis**

**Exploratory Data Analysis**

**Conclusions**

### Dataset and Ethics for Using API

I created my own dataset using the Google YouTube Data API. According to the YouTube API guide, using the API is free within certain request limits (default: 10,000 requests per day). Data obtained is public, ensuring privacy is not a concern. The data is used solely for research purposes and not for commercial use.

### My Insights

- The more likes and comments a video has, the more views it gets (correlation, not necessarily causation).
- Likes are a better indicator for interaction than comments, following the "social proof" concept.
- Most videos have between 5 and 30 tags.
- Most-viewed videos tend to have an average title length of 30-70 characters; extremes may harm viewership.
- Videos are usually uploaded on Tuesdays and Fridays, while weekends, especially Sundays, are less popular for new uploads.
