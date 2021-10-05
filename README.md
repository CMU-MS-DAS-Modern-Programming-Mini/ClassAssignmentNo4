# Class Assignment #4 - pandas

## Introduction

This homework assignment will test basic operations in a COVID-19 US data set. 

The dataset we will be working with is the NYTimes Open COVID-19 case and death data by US County.

You can download the CSV file here: https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv

The NYTimes provides up to date open data on case counts nad death for COVID-19 through their GitHub Repository at: https://github.com/nytimes/covid-19-data

## The Assignement

You are to create a Jupyter Notebook that calculates the following items for the data:

1. A DataFrame that contains the top 10 Counties data by total deaths over the time period.
2. A DataFrame that contains the top 5 States data by total deaths over the time period.
3. Calculate the incidence (the number of new cases per day... i.e. the difference between the cases on a day - the cases on a previous day) for the top 10 Counties.
4. Calculate the peak incidence for the 10 counties (the day with the highest number of new cases).
5. Plot an incidence curve for the County with the highest peak.
6. Plot a vertical bar graph with County as the category and the peak incidence as the measure.

## To create the notebook.

The Notebook is started for you:

1. Fork this repository

3. Create a virtual env
```bash
python -m venv venv
```

1. Install the modules needed
```bash
source ./venv/bin/activate
pip install -r requirements.txt
```

1. Open Jupyter Notebook
```bash
jupyter notebook
```

1. From the menu, open the blank notebook and begin the assignment

1. When completed, submit a pull request with the reviewer as `shots47s`.


