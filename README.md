"# ada-2020-project-milestone-p3-p3_hitwhunb" 

Milestone P3:


1.   Title: A large-scale analysis of racial disparities in police stops across the United States
2.   Abstract
      First, we propose to use different ways with the same dataset to find out whether the traffic stop data reflects the bias. To do so, we will build an additional                 dataset of population composition of all states in US and calculate the coefficient of the population percentage of a state and its stop rate. If a state has high              percentage of Hispanic or black men, we call this state diverse state, otherwise poor-diverse state. If the poor-diverse state has significantly higher stop rate               coefficient, we can conclude that there might be a bias in search decision. Next, we can calculate the coefficient of the population percentage of different races          and their inferred threshold in some states to further verify whether there exists bias. Finally, we want to see whether political parties have effects on the traffic          stops, we focus on two classes of states (the ticket warehouses to Democrats and Republicans) and see if the two classes of states have obvious differences in            the traffic stops.
3.   Research questions
      1. Is there a difference in the stop rate coefficient of different races?
      2. Whether the inferred threshold of a certain race is related to its population proportion in a state?
      3. Does the proportion of the minority population in a state affect the police's parking search decision?
      4. Whether there are some differences of traffic stops between states which are ticket warehouses to Democrats or Republicans?
4.   Proposed datasets
           a. "stop rate"(opp-stops state.csv) from the paper -- This dataset includes the information about stop rate data of different states.
           b. "inferred threshold"(opp-stops state.csv) from the paper -- This dataset includes the inferred threshold data of some specific states.
           c. population composition of each state from "www.census.gov/quickfacts"-- This dataset lets us know the racial composition of all states in America.
5.   Methods
      1. Data collection: use crawler to get the dataset(c) (population composition of different races in each state) and enrich the dataset.
      2. Create new data: once we have all the required data, we will use the Python Pandas to create new dataframe to calculate the coefficients of population                       percentage with stop rate and inferred threshold, and stop rate difference of the two political classes of states (optional: use kmeans to cluster the data). We              can also combine some characteristics of the data to some new features to use to analyze.
      3. Data analysis: we are interested in the differences in the stop rate and inferred threshold coefficients of different races, so we will them to analyse whether the           proportion of the minority population in a state affects the police's parking search decision. Also, we will use the difference of traffic stops between two                       political classes of states to analyse if the political parties have effects on the traffic stops.
6.  Proposed timeline
      Week 1: download the population composition datasets, and format the datasets, preprocess the data to capture some characteristics or features. 
      Week 2: choose, plan and implement the main procedure and algorithms, data analysis is during the whole process.
      Week 3: continue with analysis and optimize the algorithms, improve the initial ideas and results, prepare the data story and the short video.
7.  Organization within the team
     week 1: all members work together to collect and organize data, and discuss, understand the content of the dataset and complete specific data preprocessing.
     week 2: assign specific questions to each member to complete. Yixin Cheng will work on question 1 and 3, Jiaqi Wang will work on question 2 and 3, Xiangcheng                     Cao will work on question 4.
     week 3: all members will focus on preparing all needed figures and examples, writing the data story and report. And according to the time situation and the                             division of labor, the members complete the short video recording and conclusion arrangement.

