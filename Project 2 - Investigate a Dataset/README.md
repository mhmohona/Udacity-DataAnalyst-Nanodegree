# Dataset investigation from Gapminder World: Growth in Communication Technologies in different countries of the world from 2007-2016 and comparison with per capita income.

This project was completed as part of the course requirements for Data Analyst Nanodegree with Udacity.

# Instructions from Udacity

## How do I Complete this Project?
This project is connected with the [Introduction to Data Analysis](https://classroom.udacity.com/courses/ud170) course, but depending on your background knowledge, you may not need to take the whole class to complete this project.

## Introduction
For the final project, you will conduct your own data analysis and create a file to share that documents your findings. You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers. You will not be required to use inferential statistics or machine learning to complete this project, but you should make it clear in your communications that your findings are tentative. This project is open-ended in that we are not looking for one right answer.

## Step One - Choose Your Data Set
Click this link (available in a Google doc here) to open a document with links and information about data sets that you can investigate for this project. You must choose one of these datasets to complete the project.

## Step Two - Get Organized
Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:
- The report communicating your findings
- Any Python code you wrote as part of your analysis
- The data set you used (which you will not need to submit)

## The report communicating your findings
Any Python code you wrote as part of your analysis
The data set you used (which you will not need to submit)
You may wish to use a Jupyter notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately. If you would like a notebook template to help organize your investigation, you can click here. Or there may be a page in the project here called Project Workspace: Complete and Submit Project, where you can do all your work and submit the project.

## Step Three - Analyze Your Data
Brainstorm some questions you could answer using the data set you chose, then start answering those questions. You can find some questions in the data set options to help you get started.

Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and pandas where they are appropriate!

## Step Four - Share Your Findings
Once you have finished analyzing the data, create a report that shares the findings you found most interesting. If you use a Jupyter notebook, share your findings alongside the code you used to perform the analysis. Make sure that your report text is contained in Markdown cells to clearly distinguish your comments and findings from your code work. You should also feel free to use other tools and software to craft your final report, but make sure that you can submit your report as an HTML or PDF file so that it can be opened easily.

## Step Five - Review
Use the Project Rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project!



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
