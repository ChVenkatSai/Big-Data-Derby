# Big-Data-Derby
This Kaggle project analyzes Big Data Derby's dataset, provided by NYRA and NYTHA, to identify factors impacting racehorse performance and injury risk. Through data mining, machine learning, and statistical modeling, we uncover insights into crucial racehorse outcomes. 
## Big Data Derby 2022 Kaggle Competition - README

This README file provides an overview of the Big Data Derby 2022 Kaggle competition project undertaken by Dimple Naresh Nachnani, Sree Sai Ankit Rao Pittala, and Venkata Sai Chelagamsetty from Purdue University. 

### Abstract
The project focuses on analyzing horse racing data to generate actionable insights and predictions using data mining and machine learning techniques. The goal is to improve horse health, racing strategies, and overall performance. The dataset provided by NYRA and NYTHA is utilized to explore horse-tracking data and identify patterns, factors affecting performance, and potential strategies for race optimization.

### Dataset Details
The Big Data Derby 2022 dataset consists of four files: nyra_start_table.csv, nyra_race_table.csv, nyra_tracking_table.csv, and nyra_2019_complete.csv. The team primarily used the nyra_start_table.csv, nyra_race_table.csv, and nyra_2019_complete.csv files for exploratory data analysis (EDA). The dataset includes various features such as track ID, race number, program number, weight carried, jockey information, odds, distance, position at finish, course type, and purse value.

### Data Cleaning and Transformation
The team followed traditional data mining processes, including cleaning and transforming the data for analysis and input to machine learning algorithms. This involved importing the dataset into a data frame, handling missing values, and converting data types as needed. A new data frame was created by joining the start and race data frames to focus on relevant attributes for analysis and prediction.

### Exploratory Data Analysis (EDA)
The EDA phase involved analyzing the dataset to gain insights into various aspects of horse racing. The team made several observations based on the analysis:

1. Race Distribution: The dataset contained records of 2000 races across three different tracks (AQU, BEL, SAR). SAR had the fewest number of races.

2. Race Tracks: The distribution of races throughout the year indicated that AQU races were played in the initial and final months, while BEL and SAR races were played in the middle months, suggesting a racing season from November to October.

3. Horse Performance: Analysis of horse performance revealed the top-performing horses and jockeys across different race tracks. The data also highlighted the skewed nature of the dataset, with certain horses participating in more races than others.

4. Race Types: The team categorized races into different types based on furlong ranges, such as Juvenile races, Classic Sprint Distance races, Classic Horse races, and Long Distance races. However, the dataset did not have exact matches for all furlong values, requiring bucketing of races into the defined categories.

5. Horse Health: The impact of jockey weight on horse performance was analyzed, indicating that overweight jockeys may negatively affect race outcomes.

Algorithms Implemented: The team implemented several algorithms for prediction and analysis, including Random Forest, Boosting, Bagging, and Neural Networks.

