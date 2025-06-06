# Data Science Industry Analysis: Salary Distribution, Job Availability, and Work Flexibility

## Repository Outline
This analysis aims to comprehend the variations in salary distributions, job opportunities, and cost of living between the US and certain Asian countries. Our goal is to shed light on the question of whether increased salaries are warranted by the elevated living costs, and to help job seekers and employers make well-informed choices in light of this information.

total file:

1. README.md - Explanation of the project overview
2. Comparing Data Scientist Salary (US vs. Asia).ipynb - Notebook containing data processing and analysis with python
3. ds_salaries.csv - dataset containing 2023 data science salaries
4. index_living_cost.csv - dataset containing 2024 cost of living index



## Problem Background

### Specific:

    - Deciding whether US or Asia is the best choice for job seeker in data science industry considering the salary, job distribution, remote-ratio, and living cost of index per country.

### Measureable:

    - Using dataset based on 2023 data scientists salary
    - Comparing salary from US and Asia
    - Comparing job distribution from US and Asia
    - Analysis number of remote ratio based on selected countries
    - Comparing cost of living index on selected countries

### Achievable:

    - Analysis was done in 1 week with the available dataset, including cost of living index as a supporting dataset

### Relevant:

    - Assisting job seekers in making a choice about pursuing a career in the US or Asia, considering factors such as salary, job distribution, remote work ratio, and cost of living index.

    - Assisting businesses in determining whether the salary offered is competitive, if the number of job postings should be increased, and whether remote work is a feasible option for attracting international talent more effectively.

### Time-bound:

    - Analysis done in 1 week
    
    - Dataset use from 2023 to keep the relevancy

As data science roles expand globally, job seekers must choose between high salaries in the US or more accessible roles in Asia. Beyond pay, factors like living costs, job availability, and experience distribution matter. This analysis compares salaries, job trends, and living expenses to help job seekers and employers make informed decisions.

## Project Output
This project analyzes salary distribution, job availability, and living costs across the US and Asia, providing insights for job seekers and companies on market trends and career decisions.

## Data
This dataset covers global data scientist salaries in 2023, with 3,755 rows and 11 columns. It has no missing values, 1,171 duplicates, and key variables like experience level (4 types), employment type (4 types), job titles (93 unique), salary currencies (20), employee residences (78), company locations (72), and remote ratios (3 categories: remote, hybrid, on-site).

## Method
This project uses descriptive statistics, data visualization, correlation analysis, hypothesis testing, and categorical analysis to examine global data science salaries. We analyze salary distributions, job trends, cost of living, and remote vs. on-site work to provide insights for job seekers and employers.

## Stacks
```
import pandas as pd
import numpy as np
from scipy import stats
import matplotlib.pyplot as plt
import plotly.express as px
import seaborn as sns
from scipy.stats import kendalltaur
```


## Reference

https://www.kaggle.com/datasets/henryshan/2023-data-scientists-salary/data

https://www.kaggle.com/datasets/myrios/cost-of-living-index-by-country-by-number-2024

https://public.tableau.com/app/profile/zaky.rizky/viz/P0M1_Zaky_Rizky/AnalysisStatisticInferential?publish=yes

---