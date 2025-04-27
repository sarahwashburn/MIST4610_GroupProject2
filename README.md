# MIST4610_GroupProject2

Dylan Kiperman https://github.com/dylankiperman?tab=repositories

Sarah Washburn https://github.com/sarahwashburn?tab=repositories

Marshall Massey https://github.com/MMassey25?tab=repositories

Aay Bel Pa Pa Minn https://github.com/AayBelPaPaMinn?tab=repositories

Nimay Patel https://github.com/NimayPatel?tab=repositories

# Describing the Data: Leading Causes of Death in the U.S. from 1999-2017 (National Center for Health Statistics)
The dataset shows leading death causes in the United States for each year plus each state. It contains over 10,000 entries with cause of death, death count along with age-adjusted death rate. Each row contains data for a specific cause in a specific year and place. It includes every state besides overall national figures. Because it considers age differences, the age-adjusted death rate helps people make reasonable comparisons between states. The dataset lacks missing information, so it is simple to use. It is good to spot trends and analyze public health changes through time. From this project in particular, we answered questions such as, "What states saw the biggest rise in suicide deaths over time?" also "What states now have the highest cancer age-adjusted death rates?" These questions are important because they can help point out where certain health issues are getting worse and where more attention or resources might be needed. Overall, the dataset is a valuable resource for studying trends in mortality and gaining insight into how public health challenges vary across the country.

# Questions we Generated - Why are they important?:
1. Which states have the most deaths caused by cancer?
   
This question is important, as cancer is one of the leading causes of death in the United States. As it is currently incurable, it is important to identify which states have the highest causes of death by cancer so that preventative measures can be put in place. We first parsed through our dataset and examined all the different causes of death that were listed (heart disease, cancer, Alzhiemer’s, stroke, etc.). We consistently noticed that cancer was a leading cause of death over every year of data recorded. Bringing awareness to the states that are ravaged the most by cancer can be critical to helping those states with more patients. More cancer centers and rehabilitation centers can be built in these areas to make an impact and help our country beat cancer. By pinpointing certain states with most victims of cancer, we can make a difference and save lives.


2. Which states have the highest growth rate in deaths caused by suicide?
   
We chose to find the growth rates from 1999-2017, and then predict them over the next 10 years. This would allow us to compare our forecasted suicide deaths for each state to real-time data and test if our predictions were viable. Suicide is an extremely prevalent issue in the United States and has unfortunately claimed many lives too early. By identifying the states with the highest suicide deaths over time, we can predict which areas we need to establish the most support in. For example, in the states with the largest number of deaths due to suicide, more mental health rehabilitation centers can be built to give people access to help. More employees can be on stand-by and be trained in these specific situations to be the most effective. Overall, this research will provide impactful insights that can save lives.


# Manipulations


# Analysis and Results

1. 
<img width="611" alt="Screenshot 2025-04-27 at 4 02 59 PM" src="https://github.com/user-attachments/assets/8a3ffa30-4f99-44db-93a1-d90f9e3b4218" />

<img width="1039" alt="Screenshot 2025-04-27 at 4 03 19 PM" src="https://github.com/user-attachments/assets/4248d1ef-a32d-451e-965d-4461916483aa" />

<img width="1045" alt="Screenshot 2025-04-27 at 4 03 47 PM" src="https://github.com/user-attachments/assets/91f32b2a-6c4d-4dc4-9073-df9c930b632e" />

2. .

<img width="791" alt="Screenshot 2025-04-27 at 4 04 41 PM" src="https://github.com/user-attachments/assets/a32bd614-aa34-4a33-8010-420d2433db96" />

<img width="805" alt="Screenshot 2025-04-27 at 4 04 52 PM" src="https://github.com/user-attachments/assets/84a6ccea-f50d-42d9-a224-17c61fbd4d59" />

<img width="471" alt="Screenshot 2025-04-27 at 4 05 03 PM" src="https://github.com/user-attachments/assets/112a62f7-4ea1-47fb-a5a6-90c7bcd0df52" />


Cancer Deaths

Analysis 

One main error contributing to the heavily left skewed graph would the population difference between each state. The higher the population, predominantly more the deaths. To eliminate the bias, we took the 2010 deaths related to cancer for each state and based them per 100,000 people. So instead of Georgia having 15435 deaths in 2010, they have 159.33 deaths per 100,000 people. California had the highest cancer related deaths, but West Virginia had the most cancer related deaths per 100,000 people. Alaska had the lowest cancer related deaths, but Utah ended up with the lowest deaths per 100,000.

The biggest difference between the US average and the West Virginia average comes around the idea of lung cancer. West Virginia has the second highest tobacco use rate in the united states. However on the opposite end, Utah has the lowest rate of tobacco use which could point to why Utah has the lowest amount of cancer deaths per 100,000 people.

Implications of Analysis

From 1999-2017 it was found that California, Florida, Texas, New York, and Pennsylvania had the 5 highest number of death related to Cancer. Inversely, Alaska, Wyoming, Washington D.C, Vermont, and North Dakota had the 5 lowest amounts of cancer related deaths in the United States. This graph is heavily skewed to the left side due to one significant factor.

The bar graph was highly appropriate for our descriptive question and  type of data. We were working with discrete categories which are the different states, hence, a bar graph was ideal for clear comparisons. Initially, our raw dataset presented around 50 states, over the span of 19 years, with the highest number of deaths standing at approximately 1,050,000. Overall, a bar graph can handle large numerical differences effectively & present categorical data clearly.




Suicide Deaths 

Analysis 

Population is not a contributor to bias because we are looking at growth rate of suicides across multiple years. When looking at the visualization and the growth rate by state, a way to test the reliability of the growth rate is looking at a forecast trend line. So we took the estimated number of deaths in 2022 per the forecast line, an compared it to the actual number of deaths in 2022 caused by suicide. 

We found 38 over estimated, 12 underestimated, and 1 exactly the same. Nevada ended up having the exact same predicted value to actual value in 2022, showing the reliability  and accuracy of the Nevada trend line. In this scenario, overestimated is much better than underestimated in real life comparison.

Implications of Analysis

A line graph was highly appropriate for our analytical question & type of data. We were working with discrete categories which are the different states, hence, a line graph was ideal for showcasing trends in suicide deaths over time & identifying which states have the highest growth. Compared to the bar graph, the line graphs clearly revealed the upward & downward trends. The side-by-side table with percent change values highlighted the most extreme and least affected areas. Overall, the visualization made it easy for viewers to draw comparisons across all 50 states in one glance and look at the specific states.


# Tableau Packaged Workbook

