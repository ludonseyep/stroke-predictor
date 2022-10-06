# stroke-predictor (Machine Learning Coding Challenge 2021)

This was a group project from my Computer Science Module at Imperial College London.

## Prompt

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. As a data scientist, you are requested to provide help in understanding this problem by analysing the data. In particular, the WHO wants to understand what are the key variables that most correlate to the occurrence of strokes, so that the correct policies can be implemented. It would also be desirable to understand which variables are instead not that important, so that the limited available money can be allocated accordingly.

## Approach

1. Data preprocessing (cleaning, encoding, etc)
2. Classifier selection, training, and testing
3. Analysis of the predictivity of the classifier, depending on the parameters (gender, age, hypertension, bmi, ...)
4. Present the relative importance of the parameters using an interactive graph

## Setup

We used Anaconda when building the project. All needed libraries were readily available when using Jupyter Notebook from the [Anaconda Navigator](https://www.anaconda.com/). In the case where you are using any other IDEs, you can install the needed libraries by running:

```bash
$ pip install numpy
$ pip install pandas
$ pip install matplotlib
$ pip install sklearn
$ pip install statistics
$ pip install csv
$ pip install seaborn
$ pip install plotly
$ pip install plotly.express
```

