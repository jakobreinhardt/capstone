### Table of Contents

1. [Project Description](#description)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Credits](#credits)


## Project Description <a name="description"></a>

This is an analysis of COVID data.
The repository contains the work for the capstone project of the Data Science Nanodegree on Udacity.
A blogpost showcasing the motivation, research questions, method, results and conclusion can be found here:
https://medium.com/@jakob.reinhardt/the-analysis-of-covid-19-data-d5ddaacce88d .
I use the dataset provided by Our World in Data (https://github.com/owid/covid-19-data/tree/master/public/data). 
The project was started on 2021-11-26. In order to work with stable conclusions about the data, 
I used the dataset downloded on that day throughout the projekt.

-------------

## Installation <a name="installation"></a>

I used python version 3.8.8


-------------
## File Descriptions <a name="files"></a>

- Work.ipynb: This Jupyter Notebook contains the data analysis. Use it with the given dataset or download a newer version of the dataset from the Our World In Data repository.

- owid-covid-data.csv : Covid Dataset downloaded on 2021-11-26

- correlation_matrix.pkl : Pikle file of the correlation matrix that includes the R and P-Values for similarity of countries. This is an output of the Work.ipynb

- model.pkl: the model used to predict total corona infections

-------------

## Credits <a name="credits"></a>

Resources and APIs that helped my in the creation of the project:

- Data from https://github.com/owid/covid-19-data
