# 📊 *The Office* Episode Analysis

Welcome to this project where we dive deep into the episodes of the beloved TV show, *The Office*! In this analysis, we’ll explore how the popularity and quality of the show evolved over its many seasons. By leveraging a dataset of *The Office* episodes, we'll investigate various trends in ratings, viewership, and episode characteristics.

---

## 📂 Dataset Overview

This analysis utilizes the dataset `office_episodes.csv`, which was downloaded from [Kaggle](https://www.kaggle.com/). It contains detailed information on each episode of *The Office*, including ratings, viewership numbers, and more. Our goal is to uncover interesting patterns in the data and understand what made certain episodes stand out.

### Dataset Path


---

## 📝 Dataset Columns

The dataset contains the following columns for each episode:

- **episode_number**: Canonical episode number (e.g., Episode 1, Episode 2).
- **season**: The season in which the episode appeared (e.g., Season 1, Season 2).
- **episode_title**: The title of the episode (e.g., "The Dundies", "Dinner Party").
- **description**: A brief description or summary of the episode’s storyline.
- **ratings**: The average IMDb rating for the episode.
- **votes**: The total number of votes received for the episode on IMDb.
- **viewership_mil**: Number of U.S. viewers (in millions) for the episode’s original air date.
- **duration**: Duration of the episode in minutes.
- **release_date**: Air date of the episode.
- **guest_stars**: A list of guest stars featured in the episode (if any).
- **director**: The director of the episode.
- **writers**: The writers of the episode.
- **has_guests**: Boolean column (True/False) indicating whether the episode had guest stars.
- **scaled_ratings**: Ratings transformed on a scale from 0 (worst-reviewed) to 1 (best-reviewed).

---

## 🎯 Key Objectives

In this analysis, we’ll be answering a few interesting questions:

1. **How did IMDb ratings change over time?**
   - Investigate trends in episode ratings across seasons.

2. **How did viewership numbers evolve?**
   - Examine the rise and fall of U.S. viewers for each episode.

3. **Did guest stars influence ratings or viewership?**
   - Analyze episodes featuring guest stars to see if they performed better in terms of ratings.

4. **Does episode length impact ratings and viewership?**
   - Investigate the relationship between episode duration and its performance.

5. **Which directors and writers had the most impact?**
   - Look at which directors and writers consistently delivered high-rated episodes.

6. **What are the recurring themes in episode descriptions?**
   - Analyze episode descriptions for correlations with ratings and viewership.

---

## ⚙️ Tools and Libraries

This project uses the following Python libraries for data analysis and visualization:

- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** / **Seaborn**: For creating beautiful visualizations and plots.
- **Scipy** / **Statsmodels**: For performing statistical analysis and hypothesis testing.
- **Numpy**: For mathematical operations and numerical analysis.

