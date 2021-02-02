# Promotion Experiment with data from Starbucks and maximizing Metrics

## Project Motivation
The goal of this project is to analyze this ranodmized dataset provided by Starbucks to see if handed promotions lead to an increase in purchases.

The data was split into training and test data. Each unique receipient can also be categorized with seven unique groups V1 to V7.

There are two main questions to answer:
1. Analyze the results of the experiment to identify the possible effect on purchases and Net Incremental Revenue
2. Build a model to identify the best customers to target with promotions to maximize the Incremental Response Rate and Net Incremental Revenue.

## Getting Started
The code should run with no issues using Python versions 3.*.

### Dependencies
- pandas and numpy for data wrangling
- sklearn for training model
- itertools to print out every possible combination of data

### File Descriptions
- Starbucks.ipynb: Python notebook to analyze the experiment results and train a model to maximize metrics
- test_results.py: Python file to test the result of the model against the solution from Udacity
- The training and test data

### Installation
Aside from a working installation of python, there is no further installation needed.

## Results
The results of the experiment showed that there is almost no difference between the control and experiment group when it comes to purchases, with or withought a promotion. With the given distribution of promotion across the train data, the company even stands to lose 2334.59 $. 

For that reason a model was implemented with the goal of finding suitable, receptive customers to show promotions which are likely to buy. The model had a balanced accuracy of about 52% with the best score being at 88%. With a distribution of promotions according to the models output, Starbucks would stand to gain 128.50 $. 

That however is definatly trivial compared to the resources needed to achieve this goal. That is why my overall recommendation on this experiment is not to drive it any further and not to give out promotions promotions in this specific context.

## Author
Philip M. Herp

## Licensing, Authors, Acknowledgements
[Udacity](https://www.udacity.com/) provided the file templates and code snippets that were used in the web app. 

[Starbucks](https://www.starbucks.com/) provided the dataset that was used to train the classifier.
