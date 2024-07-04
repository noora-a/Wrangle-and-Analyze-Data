# Wrangle and Analyze Data Project

## Table of Contents
- [Project Overview](#project-overview)
- [Files](#files)
- [Datasets](#datasets)
- [Steps](#steps)
  - [Data Gathering](#data-gathering)
  - [Data Assessing](#data-assessing)
  - [Data Cleaning](#data-cleaning)
  - [Data Visualization and Analysis](#dva)
- [Results](#results)
- [Conclusion](#conclusion)

## Project Overview <a name="project_overview"></a>
This project is part of the Data Analytics Nanodegree program on Coursera. The goal of the project is to wrangle and analyze the WeRateDogs Twitter data to derive meaningful insights. The project involves gathering data from multiple sources, assessing its quality and tidiness, cleaning it, and then performing analysis and visualization.


## Files <a name="files"></a>
- `wrangle_act.ipynb`: Notebook containing the data wrangling process.
- `wrangle_report.ipynb`: Notebook summarizing the data wrangling steps.
- `act_report.ipynb`: Notebook containing the analysis and visualizations.
- `image-predictions.tsv`: File containing the image predictions data.
- `tweet_df.csv`: Cleaned and combined tweet data.
- `tweet-json.txt`: Raw JSON data from Twitter API.
- `twitter_archive_master.csv`: Final cleaned dataset used for analysis.
- 
## Datasets <a name="datasets"></a>
The project uses three main datasets:
1. **Twitter Archive**: Provided by Udacity, containing basic tweet data.
2. **Image Predictions**: Generated by a neural network, containing predictions of dog breeds from tweet images.
3. **Tweet JSON**: Additional tweet data extracted using the Twitter API.

## Steps <a name="steps"></a>

### Data Gathering <a name="data-gathering"></a>
- Downloaded the WeRateDogs Twitter archive.
- Programmatically downloaded the image predictions file.
- Used Tweepy to query the Twitter API for each tweet's JSON data.

### Data Assessing <a name="data-assessing"></a>
- Performed both visual and programmatic assessment to identify data quality and tidiness issues in the gathered datasets.

### Data Cleaning <a name="data-cleaning"></a>
- Addressed issues identified during assessment, including handling missing data, correcting erroneous data, and merging datasets into a master dataframe.

### Data Visualization and Analysis <a name="dva"></a>
- Conducted exploratory data analysis to uncover patterns and trends.
- Visualized key insights using various plotting techniques.

## Results <a name="results"></a>
The analysis of the WeRateDogs dataset revealed several interesting insights, including:

- Most Common Dog Breeds: Labrador Retriever, Golden Retriever, and Pembroke Welsh Corgi were frequently rated.
- Distribution of Ratings: The majority of the dogs received high ratings, typically above 10 out of 10.
- Engagement Metrics: Higher ratings correlated with more favorites and retweets.
- Dog Stage Distribution: Pupper was the most common stage, followed by doggo.
- Tweet Source: Most tweets were posted using Twitter for iPhone

## Conclusion <a name="conclusion"></a>
This project demonstrates the end-to-end process of data wrangling and analysis, from gathering data from multiple sources to performing cleaning and analysis. The insights derived from the WeRateDogs Twitter data provide a deeper understanding of the trends and patterns in the dataset.

