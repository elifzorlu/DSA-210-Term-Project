# DSA-210-Term-Project
 
# ADHD Focus Analysis Project

## Project Overview

As a busy college student diagnosed with ADHD, it is super crucial for me to plan my life in a way that is easier to manage for my ADHD brain. In my daily life, I notice fluctuations in my maximum length of undisrupted focus, which led me to ponder: What if I can use the teachings from DSA 210 to make my life easier by applying it to a daily problem I face every day ? That's why I have decided to collect in-depth data of the factors that might have an impact on my maximum undisrupted focus length in a day. By analyzing factors like sleep (quality and duration), caffeine consumption, stress levels, ambient sound levels, listened to music or not, my study location, study window, number of classes I attended that day and lastly my total length of all my study sessions combined to uncover which of my daily habits and factors impact my maximum duration of undisrupted focus in a day (where I will stop my timer after I feel like my mind is wandering away from my study). Using data visualization and statistical tools, I’ll explore patterns and test what changes in my life can lead to measurable improvements. 

The plan is simple: track my daily factors and routines, correlate them with my undisrupted focus performance, and test hypotheses about what really makes a difference. Ultimately, I want this project to provide actionable insights to help me plan my study sessions. By tracking my daily habits, environmental conditions, and mental state, I aim to transform raw data into actionable insights that can help me—and potentially others with ADHD—optimize our routines and unlock our full potential.

---

## Objectives

1. **Understand Performance Influencers**  
   Explore the relationship between sleep, caffeine consumption, stress levels, ambient sound levels, listened to music or not, study location, the study window, number of claases I attended that day and lastly my total length of all my study sessions combined to uncover which of my daily habits and factors impact my maximum duration of undisrupted focus in a day 

2. **Identify Key Factors**  
Identify the variables that have the most significant influence and design a targeted strategy to maximize undisrupted focus duration.

3. **Optimization Driven by Data**  
Leverage the insights gained from the analysis to meticulously refine my daily routines, thereby consistently enhancing my performance.

4. **Apply Data Science Skills**  
Apply the concepts I’ve learned in my DSA 210 course to real-world scenarios, deepening my comprehension of data analysis and visualization.

---

## Motivation

In this project I aim to use my data skills in order to make my life easier and optimize my focus duration, and here is why it matters:

- **Personal Growth** 
Discovering what affects my focus majorly will help me plan my days and habits accordingly, where I will be able to guess how much focusing I can do in a day considering my stats for that day, helping me approach my tasks more realistically.
  
- **Scientific Approach**  
I want my progress to be guided by data rather than mere guesswork. This project provides me with the necessary tools to analyze and refine my approach.
  
- **Practical Application**  
It presents an opportunity to apply the theoretical knowledge I’ve acquired in class to a significant and practical project.
  
- **Long-Term Impact**  
I will take my findings into consideration and make changes to my habits and daily routines in order to maximize my productivity.
---

## Dataset

The dataset for this project consists of months of daily records. Here’s what I’ll be tracking:

- **Date**: The specific day of the record
- **Sleep Duration**: Total sleep duration (hours)
- **Sleep Quality**: Ratings from the Sleep Cycle app (scale of 1–10)
- **Caffeine Consumption**: Total amount of caffeine intake in a day (mg)
- **Music Usage (Yes/No)**: Whether I have listened to music or not during my peak focus
- **Amount of Classes Attended**: I will report the number of classes I have attended that day to measure my mental fatigue.
- **Stress Levels**: Objective biometric stress level measurement from my Huawei smartwatch (scale 1-10)
- **Ambient Sound Level**: The average ambient sound in the background while studying (dB)
- **The Study Window**: The hour window where my maximum duration of undisrupted focus has occurred
- **Study Location**: The place where my maximum focus has occurred (dorm room vs. library vs. home)
- **Total Study Duration**: I will report the total amount of studying done in that day.
- **Undisrupted Focus Length**: My maximum duration of undisrupted focus while studying (and continuing until I realize my mind is wandering and I'm not being productive) (mins)

I’ll diligently log all these data points daily in an Excel file and collect them. I’ll also flag any outliers caused by illness or significant routine changes for review.


---

## Tools and Technologies

I’ll rely on the following tools for data analysis and visualization:

- **Python**: For data cleaning and statistical analysis  
- **Pandas**: To manipulate and preprocess data  
- **Matplotlib and Seaborn**: For creating visualizations (scatter plots, heatmaps, time series)  
- **SciPy**: For hypothesis testing and regression analysis  

---

## Data Collection Methods

This is how I will be collecting my data: 

- **Sleep Quality & Sleep Length**: I will derive this data by using an app called Sleep Cycle on my phone where I will place my phone close to my bed. I will use hours to measure my sleep duration and a scale 1-10 to measure my sleep quality as provided objectively and scientifically by the app I mentioned.
- **Stress Levels**: I will use my Huawei smart watch to measure my stress levels. Objective biometric stress level measurement from my Huawei smartwatch (scale 1-10)
- **Caffeine Consumption**: I will use the data available on the website of the coffee place to measure the amount of caffeine per drink. (mg)
- **Ambient Sound Levels**: I will use an online tool via my laptop to measure the average ambient sound levels during my peak focus, in decibels. (the website: https://www.checkhearing.org/soundmeter.php)
- **The Study Window**: I will report the study window by using the clock. (e.g. morning (7.00 am - 12.00 pm), afternoon (12.00 pm - 05.00 pm), evening (05.00 pm - 09.00 pm), night (09.00 pm - 07.00 am))
- **Amount of Classes Attended**: I will report the number of classes I have attended that day to measure my mental fatigue.
- **Study Location**: I will record the location where my maximum focus has occurred. (e.g. dorm room vs. library vs. home)
- **Total Study Duration**: I will report the total amount of studying done in that day by using the Forest app in total numbers of hours of study format.
- **Undisrupted Focus Length**: I will record all of my study sessions using a productivity app called Forest where it blocks all distractions from my phone. I will check the records on this app daily to pinpoint my maximum focus duration in a single session. As a note, in every study session I will keep studying until I realize my mind is involuntarily swaying into non-study related thought and stop the timer when I realize my study session is not being productive anymore (I will not leave my seat during my sessions nor change anything that might affect my study session).

---


## Analysis Plan

1. **Data Collection**  
   - Import daily Excel records into a Pandas DataFrame and preprocess the data by handling missing values and standardizing units.  

2. **Visualization**  
   - Use scatter plots, heatmaps, and time series plots to explore relationships between variables.  
   - Examples include:
      - Heatmap showing correlations between all variables  
     - Scatter plot of sleep quality vs. maximum focus duration  
     - Time series plot comparing performance trends over the months  

3. **Hypothesis Testing**  
   - Test hypotheses like:  
     - **H₀**: Daily habits have no effect on the duration of my maximum undisrupted focus.  
     - **Hₐ**: One or more daily variables significantly impact the length of my maximum undisrupted focus.  
   - Run regression analysis to identify the strongest predictors of maximum undisrupted focus duration performance.
   - Test for interaction effects between variables (e.g., sleep quality × caffeine intake).

4. **Trend Analysis**  
   - Investigate patterns in performance over time, identifying peaks or plateaus.  
   - Analyze how number of classes in a day and day-to-day stress levels ratings correlate with performance trends.
  

 5. **Predictive Modeling**

   - Develop a simple model that can estimate focus capacity based on morning conditions
   - Test and refine model accuracy over time
   - Create practical decision rules (e.g., "If sleep quality < 6, then increase caffeine by X")

---

## Example Analysis

To demonstrate this, I’ll generate a scatter plot to visualize the correlation between sleep quality and undisrupted focus length performance. The x-axis will represent the sleep quality from the night before (scale 1-10) using the data from an app called Sleep Cycle, and the y-axis will show my undisrupted focus length (minutes). If there’s a clear upward trend, it might suggest a strong correlation between sleep quality and focus length fluctuations.

Another example involves comparing performance on high-stress level days (e.g. stress levels =  7-9) versus low-stress level days (e.g., stress levels = 1-3). This could reveal how mental and physical stress impacts my focus.

Similarly, I intend to monitor my stress fluctuations over time and examine their relationship with my ability to concentrate. For instance, if improvements in stress coincide with extended periods of uninterrupted focus, it could imply that factors like number of classes I had that day and caffeine consumption negatively impact my stress levels. Furthermore, I’ll observe variables such as sleep patterns, caffeine consumption, stress levels, total study time, music usage during study, study location, study window, and ambient noise. I’ll also explore whether certain combinations of factors—like music usage and ambient sound levels- may interact to produce specific outcomes, such as enhanced focus or stress levels fluctuations.

For feature importance analysis, I'll use techniques to rank which variables most strongly predict focus duration. This might reveal that while I've been prioritizing caffeine management, perhaps sleep quality is actually three times more impactful.


---

## Conclusion

By the end of this project, I hope to answer:
 
This project will not only help me manage my ADHD more effectively but also deepen my understanding of data science concepts.

- Which factors most influence my focus length?
- Can I predict focus length based on morning conditions?
- Which combinations of factors (e.g., sleep quality + caffeine intake) produce the optimal focus conditions?
- Are there interaction effects (e.g., sleep quality × caffeine intake)?
- Is there a threshold effect for certain variables (e.g., minimum hours of sleep needed)?
- How does sleep play a role in my focus performance?
- How can I optimize my routines to improve focus?

This project goes beyond merely exploring the impacts of my ADHD brain and its maximum focus length. It also aims to use data science to effectively manage the effects of ADHD on various aspects of my life. Whether it’s mental health, productivity, or learning, comprehending the numerical indicators behind performance is crucial for achieving success; it aims to use data science to develop better self-management strategies.


---

I'm looking forward to figuring out what data uncovers and use this project to help ease the obstacles that are accelerated by my ADHD,
by discovering which factors I can manage in myself into my most efficient and productive self!
