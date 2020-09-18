# Dataset investigation from Gapminder World: Growth in Communication Technologies in different countries of the world from 2007-2016 and comparison with per capita income.

This project was completed as part of the course requirements for Data Analyst Nanodegree with Udacity.

# Introduction
In this project we have analysed real-world socio-economic datasets using python and its libraries
The world has witnessed a tremendous progress in the field of communication technologies in recent years. Although the technology for tools such as the Internet, the mobile phone, home wireless networks, etc has been available for many years, the rate of diffusion for these technologies has seen significant changes in recent years. For this project, I have chosen to analyse the growth of some communication technologies in different countries throughout the world, based on their per capita income. 

The data obtained is investigated and analysed in an attempt to find the answers to the following questions:

**How do different countries in the world, based on their per capita income, compare in their use of the following communication technologies during the period 2007-2016: Broadband subscribers, Cell phones, Internet users. Is there any relation between the per capita income and the use of these communication technologies?**

**Is there any noticeable trend that can be observed in the use of these communication technologies over the years between 2007-2016?**

# Project Description
The datasets used in this project have been chosen from Gapminder World. https://www.gapminder.org/data/

Gapminder has collected a lot of information about how people live their lives in different countries, tracked across the years, and on a number of different indicators. From the website, the datasets are obtained by choosing the following indicators:

Category: Infrastructure, Sub Category: Communication, Datasets:

                           1. Broadband Subscribers (total)
                           2. Cell Phones (total)
                           3. Internet Users(total)

Category: Economy, Sub Category: Incomes & Growth, Dataset:

                           4. Income per person (GDP/capita, PPP inflation-adjusted)

These data is then cleaned, wrangled and then Exploratory Data Analysis is performed using python and its libraries numpy and pandas. We have investigated trends in the growth in use of different communication technologies (broadband, cell phones and internet) in all countries of the world. The countries have been segmented into different categories Group1 - Group 5 based on their per-capita income, with Group 1 countries having the highest per-capita income and Group 5 the lowest. . We then investigated trends in the growth in use of different communication technologies between 2007-2016 the relation with the country’s per capita income. Presented findings with relevant statistics and visualizations using the matplotlib library.

# Technologies Used

Python

Libraries: pandas, numpy, matplotlib

Jupyter Notebook

# Results

We gained some insights on the growing use of communication technologies throughout the world, and seen how it compares with the country's GDP.

1. In terms of broadband use, Group 1 countries with the highest per capita income has always ranked the highest. The number of broadband users decreases as the per capita average income decreases, and Group 5 countries with the lowest per capita income has the least number of broadband users for all years. The number of broadband users in Group 1 countries is significantly (approximately 20 times) higher than Group 5 countries. The trend shows a decreasing trend of broadband users from higher income countries to lower income countries.

2. In terms of cellphones use, we observed less significant differences than broadband use. Here, Group 3 countries are observed to have the most number of users, followed by Group 1 countries, although the difference margin is smaller. Thus medium income countries (average per capita income 10000-30000) have recorded highest number of cell phone users. 

3. Internet user trends follow a similar trend to broadband use. Group 1 countries have highest number of users, and the number of users falls with the country's per capita income. Group 5 countries have recorded lowest number of users. The difference is appreciable.

4. The number of broadband, cellphones and internet users has maintained an increasing trend every year from 2007-2016. This is consistent for countries in all income groups and for all communication means, but the trend is more pronounced in the earlier years of the decade compared to the later years.
