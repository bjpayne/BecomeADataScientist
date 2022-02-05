### Table of contents

1. [Installations](#installations)
2. [Project Motivation](#project-motivation)
3. [File Descriptions](#file-descriptions)
4. [Usage](#usage)
5. [Sources](#sources)

## Requirements

Python 3.*

Numpy

```bash
pip install numpy
```

Pandas

```bash
pip install pandas
```

Matplotlib

```bash
pip install matplotlib
```

Scikit-Learn

```bash
pip install scikit-learn
```

Jupyter

```bash
pip install jupyter
```

Seaborn

```bash
pip install seaborn
```

## Project Motivation

I wanted to answer the following questions about AirBnb data in Seattle area:

1. What is the busiest time of year to visit Seattle?
2. What is the price delta when visiting at various times?
3. Can a price prediction model be built to predict a price of a listing?

## File Descriptions

Each question has a corresponding notebook that details how I attempted to answer that question.

question1.ipynb - Explore the data to figure out when is the busiest time of year to visit Seattle
question2.ipynb - Further explore the data to figure out when is the most expensive time of the year to visit Seattle
question3.ipynb - Using the data from the first 2 questions, build a model to predict the price of a listing using the
categorical columns available in the listings file

calendar.csv, listings.csv, reviews.csv - Kaggle data on Seattle AirBNB listings

## Results

Question 1 - The months with the most openings are in the early and latter part of the year. Summer is the busiest
time of year to visit Seattle.

Question 2 - The summer is also the most expensive time of year to visit Seattle

Question 3 - There is sufficient data, and the data is relatively clean enough to support a model that has consistent,
but lower rsquared values. However, further analysis could get these values higher and provide a more accurate model.

## Sources

https://www.kaggle.com/airbnb/seattle?select=calendar.csv

https://pandas.pydata.org/docs/reference/index.html
