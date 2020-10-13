# DATA_602_Project_1
## Overview

The goal of this project was to select an appropriate model to fit a selected dataset. I created my data set by scraping the [U.S. Bureau of Labor Statistics website]( https://www.bls.gov/ooh/a-z-index.htm) with the goal creating a prediction model for job availability in 2029. In addition to web scraping, this project demonstrates techniques relevant to UMBC’s DATA 602 class, like Linear Regression, Decision Trees, and K-fold Cross Validation.

# Motivation

Job creation and automation has been a deeply American issue since at least the days of the Industrial Revolution. With technology on the rise, it truly only a matter of time before we see the next industry overtaken by machines. Fortunately, this isn’t all bad news for the average American. The U.S. Bureau of Labor Statistics projects and increase of 30 million jobs in the U.S. job market over the next 10 years. The challenge I hope to address is to understand where those jobs are going, and how to best predict, and prepare for the future ahead.

## Navigation (Need to link notebooks)

[Technical Notebok](https://github.com/miles-frankllin/DATA_602_Project_1/blob/main/Notebooks/Technical_Notebook.ipynb) -
[Web Scraping NoteBook]( https://github.com/miles-frankllin/DATA_602_Project_1/blob/main/Notebooks/Web_Scrapping.ipynb) –
[Exploration NoteBook](https://github.com/miles-frankllin/DATA_602_Project_1/blob/main/Notebooks/Exploratory_Analysis.ipynb) -
[BLS Data](https://www.bls.gov/ooh/a-z-index.htm)

## Requirements
<pre>
Languages    : Python 3.8.3
Tools/IDE    : Anaconda
Libraries    : pandas, matplotlib, numpy, sklearn, time, IPython.display, requests, bs4, string
</pre>

## Data
<pre>
File Name      : BLS_jobs_data_cleaned.csv
URL            : N/A
Limitations    : It may be helpful to add a categorical variable desribing the industry each job is a part of.
Concerns       : N/A
Dimensions     : 12393 rows × 11 columns
Columns        : URL (object), Typical Entry-Level Education (object), 
                 Work Experience in a Related Occupation (object), On-the-job Training (object), Number of Jobs, 
                 2019 (int64), Employment Change, 2019-29 (int64), Job_Title (object), Yearly_Wage (float64), 
                 Hourly_Wage (float64), Job_Outlook_2019-29_Rate (float64), Job_Outlook_2019-29_Discription (object)
</pre>

## References
<pre>
URL            : https://www.bls.gov/ooh/a-z-index.htm
Author         : N/A
Purpose        : This is the base website that I used for web scraping.
<pre>
