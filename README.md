# DSA210-Term-Project
## Analysis of the Screen Time and Physical Activity Data: How does screen time effect physical activity/performance? 

## Project Overview
Over the given weeks, I will analyze my **smartphone screen time** and **physical activity levels** using data from an **Apple Watch SE (2nd Gen)** and **iPhone Screen Time reports**. By leveraging data analysis and machine learning techniques, I aim to determine whether increased screen time correlates with decreased physical activity/performance  and how external factors like sleep and weather influence this relationship. This project will involve data collection, feature engineering, exploratory data analysis, and predictive modeling.

## Motivation
As my smartphone became one of my essentials in daily life, it also started consuming a hefty amount of time from my day. Understanding the pattern between screen time and my daily physical activity/performance will be a valuable insight for me. I will measure various factors through my smart watch and phone, and will use the weather data of Apple in order to take in the environmental changes into account. Additionally, this project will be an interactive way of developing practical data science skills through the application of data science methods to real life. 

## Objectives
- **Collect the Data:** Wear the Apple Watch daily in order to get accurate data. Use file extraction methdos to get the data into csv files.
- **Analyze the gathered data:** Process the data you collected over the weeks, analyze the correlation between screen time and exercise frequency.
- **Take into account the external data:** Examine your sleep quality, stress levels, and weather data to see the correlation between phone use and physical activity.
- **Develop a Model:** Develop a model using python to uncover trends and predict the effects of screen time on exercise.

## Research Questions
- **What is the correlation between screen time and daily physical activity levels?**
- **Do external factors such as hours of sleep and class hours moderate the relationship between screen time and physical activity?**
- **How do environmental factors (e.g., weather conditions) influence screen time and physical activity behavior?**
- **Can a predictive model effectively forecast physical activity levels based on screen time patterns and other external factors?**



## Dataset

### iPhone Screen Time Data (Gathered from my personal phone):
- **Daily screen time duration** (total hours and minutes)
- **Breakdown of screen time** by app category (e.g., social media, productivity, entertainment)
- Collection: daily tracking

### Apple Health Data (Gathered from my apple watch):
- **Daily step count**
- **Heart rate measurements** (resting heart rate and average daily heart rate)
- **Active calories burned**
- **Exercise duration** (minutes per day)
- **Sleep duration**
- Collection: through apple health data export


### Weather Data (Gathered from a weather API) :
link: https://www.visualcrossing.com/weather-data/
- **Daily temperature** 
- **Weather Conditions**
- **Humidity**
- Collection: weather api (using codes to extract weather data)

### Other:
- **Academic Schedule** (class hours & midterm weeks) 



## Timeline of the Project

**March 14th:** Start collecting the data through wearing the apple watch. Set up an automated system to extract data to a common csv file autonomously. 

**March 29th:** Use the spring break to take a look at the data you gathered, and start applying the machine learning concepts to the data to get a grasp on the basics. 

**April 18th:** Use the data you gathered to conduct explanotory data analysis methods and test your hypothesis. 

**23 May:** Apply the machine learning methods you learned on your data set. 

**30 May:** Submission deadline. 

## Hypothesis

- **Null Hypothesis:** There is no significant relationship between screen time and physcial activity levels.
- **Alternative Hypothesis:** There is a significant relationship between screen time and physical activity, with increased screen time associated with lower activity levels.


