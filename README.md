### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Medium Post](#medium)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

To run the Jupyter notebook, one needs to have the following libraries installed.

  - python: 3.*
  - numpy: 1.16.*
  - pandas: 0.24.*
  - seaborn: 0.9.*
  - matplotlib: 0.11.*
  - scipy: 1.2.*
  - sklearn: 0.*
  
If you install Python and Jupyter Notebook through Anaconda distribution, you should be all set to run the codes.

## Project Motivation<a name="motivation"></a>

This project is part of the requirements for Udacity Data Scientist Nanodegree. In this project, I want to use the survey data from Stack Overflow [here](https://insights.stackoverflow.com/survey) to answer the following questions:

  1. Do more and more people from non computer science background become developers?
  2. Does gender affect whether a developer wants to become a manager in the future?
  3. What factors affect the work hours per week for developers

## File Descriptions <a name="files"></a>

  1. `Stackoverflow_survey_analysis.ipynb`: the notebook contains exploratory data analysis, statistical analysis, and modeling on the Stack Overflow survey data for the last 3 years.
  2. `Data` directory: the directory contains the Stack Overflow survey data in the last 3 years (2017, 2018, 2019)
  3. `viz` directory: the directory contains the visualizations created from the notebook

## Results<a name="results"></a>

The results to answer the 3 questions are listed below:
  1. Based on the survey data, the trend of non-CS background people becoming developers is not increasing in the last 3 years.
  2. According to the result from the statistical analysis, gender does have influence on whether a developer wants to become a manager in the future.
  3. `Employed full-time` is the most important factors in terms of predicting the work hours by week for developers.

## Medium Post<a name="medium"></a>

  - Here's the link to my Medium post about the project and the findings - https://medium.com/@hsiaopenghsu/peek-in-the-life-of-developers-with-data-analysis-b67240657d30

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

  - The dataset for the project is from Stack Overflow survey data: https://insights.stackoverflow.com/survey
  - The project template is sourced one of the Udacity github repos: https://github.com/jjrunner/stackoverflow
