# Exploratory Data Analysis on Indian Premier League
![Image](https://camo.githubusercontent.com/ca5c8612d16d2bd6892117fece40bda92e8105e61d640712963f678a82401bc9/68747470733a2f2f77616c6c70617065726163636573732e636f6d2f66756c6c2f323330323734332e6a7067)
Indian Premier League (IPL), Indian professional Twenty20 (T20) cricket league established in 2008. The league, which is based on a round-robin group and knockout format, has teams in major Indian cities. The brainchild of the Board of Control for Cricket in India (BCCI), the IPL has developed into the most lucrative and most popular outlet for the game of cricket.   

## PROJECT DESCRIPTION
Exploratory Data Analysis (EDA) is a crucial step in the data analysis process where you visually and statistically summarize, explore, and interpret the main characteristics, patterns, and trends in a dataset.      
Let's break down the steps involved in performing EDA on the [IPL dataset](https://www.kaggle.com/datasets/nowke9/ipldata):    

Importing Libraries: You start by importing libraries like pandas, numpy, matplotlib, and seaborn to handle data manipulation, numerical computations, and visualization.     

Loading the Dataset: Load the IPL dataset into a Pandas DataFrame using the pd.read_csv() function.    

Basic Exploration: This step involves understanding the basic structure of the dataset. You can use functions like df.head() to display the first few rows, df.describe() to get summary statistics of numerical columns, and df.info() to get information about column data types and missing values.    

Data Cleaning: Before diving into analysis, it's important to clean the data. This step includes identifying and handling missing values (df.isnull().sum()), and removing duplicate rows (df.drop_duplicates()).    

Exploratory Analysis: In this phase, you generate visualizations to gain insights into the data. For example, you can create a bar plot using sns.countplot() to show the number of matches played in each IPL season. This gives an overview of the tournament's growth over the years.   

We have covered the basic analysis from IPL 2008 to IPL 2019.

1.Total number of matches played in each season  
2.Maximum and minimum matches in a season   
3.Prefered Toss decision per season   
4.Decison made after winning the toss    
5.Numbers of matches won by Toss result      
6.Has Toss-winning helped in Match-winning?     
7.Toss decision vs win/loss    
8.Total number of matches won by each team   
9.Number of wins per team    
10.Win by highest margin per season     
11.Score Distribution of Each Team for First Innings   
12.Score Distribution of Each Team for Second Innings   
13.Finding the Factors Affecting the Victory   
14.Number of times scored or conceded above 200 runs by each team  
15.City wise analysis  
16.Stadium Wise Analysis   
17.Comparing two teams  
18.MI vs CSK Head-to-Head Match Results   
19.Most Player of the Match Award Winner   
20.Numbers of six hit in each season  
Player Analysis          
21.Most Number of Maximum   
22.Most Number of Boundaries (4s)  
23.Highest Run Scorers  
24.Most Number of Half-Centuries and Centuries   
25.Most Number of Half-Centuries   
26.Most Number of Centuries   
27.Highest Scores of Each Batsman   
28.Player who got dismissed most number of times   
Bowling Analysis         
29.Kind of dismissal   
30.Bowler with most number of wickets   

## Analysis   
Click [HERE]() to view the analysis.
