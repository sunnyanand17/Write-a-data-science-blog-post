# Finding behavior of Indian programmers using stack overflow dataset
Udacity data scientist nano degree program

### Table of Contents
1. Installation
2. Project Motivation
3. File Description
4. Data Preparation
5. Evaluation
5. Results
6. Licensing, Authors, and Acknowledgements


## Installation

Use the anaconda package manager for installing jupyter notebook in which all the code developemnt and analysis is done.
Please follow the steps provided in this link based on your workstation environment. https://docs.anaconda.com/anaconda/install/

## Project Motivation

#### Dataset Description - Business Understanding
Every year, Stack Overflow conducts a massive survey of people on the site, covering all sorts of information like programming languages, salary, code style and various other information. This year, they amassed more than 64,000 responses fielded from 213 countries.

Data The data is made up of two files:

survey_results_public.csv - CSV file with main survey results, one respondent per row and one column per answer survey_results_schema.csv - CSV file with survey schema, i.e., the questions that correspond to each column name m Acknowledgements Data is directly taken from StackOverflow and licensed under the ODbL license.

#### Questions of Interest, Data Understanding

We want to know how Indian Progrmammers are using the various languages and what they want to learn as the next language.  So we asked three questions
1. Which Programming languages are most favored by Indian Programmers?
2. Which Programming languages are most desriable in India?
3. How does work place programming language influence people interest for learning the programming languages of their choice?


## File Description

You will need to download Stackoverflow’s 2017 Annual Developer Survey and put in specific folders. You can download the data and schema from this [link](https://www.kaggle.com/stackoverflow/so-survey-2017).

StackOverflow-dataset.ipynb - The notebook which contains all the analysis.

## Data Preparation

In order to perform data preparation for this analysis I performed a couple of steps to ensure the data is present in the suitable format and is used properly. The following data cleaning and formatting was applied to the original dataset.
* The column contains list of programming languages as separated by semi-colon, so we need to split the columns into series.
* The columns are grouped into 2 separate dataframes based on the processing needs.

## Evaluation

There are 3 questions asked and we evaluated the result for these three questions using the visualization technique of understanding how the data supports the asked questions. 

In the first question which programming languages have been mostly used for working in India?
Based on the analysis of the Annual developer survey StackOverflow data we can see that Javascript, Java, and SQL are the most used programming languages among Indian Developers.

In the second question which Programming languages are most desriable in India?
Looking at the most sought after languages , one can clearly see that while JavaScript reamins the most desirable language of the Indian programmers , Python has gained popularity and has jumped over Java and SQL to be the language to which most programmers are looking forward to learning.

In the third question how does work place programming language influence people interest for learning the programming languages of their choice?

While trying to understand the programmers usage of programming language at work and what they wish to learn, one wonders if the programming language used at work is somehow impacting those choices. Probably these programmers want to become expert in these work languages so that they can work more efficiently.
In order to better understand this relationship , we will look at how the programming language at work influence the choice for learning a programming language. We see the below observation from the heatmap of work vs want relationship for the programming languages.
People using a work language tend to use the same language for learning. This is evident with strong relation with people using python for learning at home when using pyhton at work

## Results

The results are shared [here](https://capricioussunny.medium.com/analyzing-kaggle-dataset-stack-overflow-developer-survey-for-indian-programmers-d8465777359a)


## Licensing, Authors, and Acknowledgements
Sunny Anand is the author of this analysis. 
The credit for data goes to both Kaggle and StackOverflow.





