# PowerBI-Data-Survery

## Table of Content
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Project Overview
In this project, we took data from a survey conducted with data professionals from around the world, of varying ages and unique stories to tell. All of this in a bid to paint a picture of just how data professionals first got introduced to data analytics, how they're getting on and other interesting information. We

## Data Sources
Data Professionals Survey Data: The primary data source for this project is "PowerBI-FinalProject.xlsx", which contains the survey responses from data professionals from around the globe.

## Tools
- Microsoft PowerBI

## Data Preparation
The data source is an "xlsx" file, so it would not be uncommon to prepare the data using the Microsoft Excel app. But since PowerBI has the Power Query interface, naturally, all data cleaning was carried out there instead. 

Since this is data sourced from survey answers, there is some degree of order to be exepected but there was still some cleaning to be done. For example, the age, salary, job titles, favorite programming languages and other columns had too much unstandardized data under the "Other" options.

For better visualization, we need standardized data, and so we set about cleaning the aforementioned columns. The 'split column' option comes in handy in this exercise as it is able to filter for the exact portions of the data in each row that we need. 

The function comes with default options, but we made use of the 'delimiter' option more as it let us split the '(' after the 'Other' option. Once the data is split into two columns, you can either do further cleaning if you need the extra data, or you can delete it like we did.

## Data Analysis
As part of this data exploration project, and considering the wealth of data at our disposal, there are indeed a ton of questions we can ask to give us insight into the lives of the average data professionals. Our analysis, however, involved the following queries;
- How many people took the survey?
- What is the average averafe age per survey taker?
- What role earns the highest on average?
- What programming language is the most preferred amongst which data professionals?
- 
