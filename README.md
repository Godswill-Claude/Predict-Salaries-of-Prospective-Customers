# Predict-Salaries-of-Prospective-Customers
This project involves building a decision tree model to predict the salaries of targeted prospective customers according to the following scenario:
Imagine you work in the finance industry and have data on people who are not yet your customers.
Your Head of Department asks you to come up with a strategy to acquire high-value customers from that data.
The execution has to be aggressive, but we need to target those customers who earn above 1,000 USD for this particular campaign.
Their salary data is not available because our data collection did not include salary data, but we have some of their attributes or features (e.g. their job title, place of work, and their highest level of education).

What can we do with this data to predict their salaries? We can use the existing data of our customers who earn above 1,000 USD to build and train a decision tree model, which can later be used on the new data to predict the salaries of these users.

This is a supervised classification problem

## Dataset
The salaries dataset was used. You can download it from this repository or online. The dataset includes features such as company, job, degree, and the target variable - `salary more than 100k`.

## Tools/Softwares/Packages Used
Python was used, along with libraries such as pandas, matplotlib and sklearn.

## Key Insights for Analysis/Investigation
In this project, I endeavored to find out the relationship each of the features company, job and degree has on the salary of the worker

## Summary of Findings
I found out that an individual who works for google, is a sales executive and holds a bachelors degree probably earns more than a 100k and belongs to the category of potential clients we are targeting for our campaign.

Generally, decision tree algorithms are referred to as CART (Classification and Regression Trees).
While they are easy to understand and implement, one limitation of them is that a small variation in data could result to a completely different tree being generated, a concept known as variance. More so, one could create an over-complex decision tree that does not generalize well on data, a concept known as overfitting (when a ML model performs very well on train data but not on test data). Another challenge is biased data. It is recommended that we balance our dataset before fitting to our model.
Ideally, we would like to mitigate the errors due to variance and bias. The random forest model does well to take care of these issues.
