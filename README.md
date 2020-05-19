# Machine Learning: Use cases in FINTECH

- The data for these projects are manufactured fields based on trends found in real-world case studies. The fields describe what companies usually track from their users, and the distributions are based on observed distributions in the real-world analysis. This means that, although the data has been artificially created, the patterns, associations, and distributions are not random.


- The data serves as a good representation of what you may encounter in the workplace. That is, the data is rarely clean, and a lot of pre-processing is needed to get it ready for modeling.
***

## Note on models Building:
The Model Building Process is composed of multiple parts:
- **Plotting with Matplotlib and Seaborn** - A lot of time will be spent on Exploratory Data Analysis (EDA)
- **Data Manipulation** - We will use Pandas and Numpy for all of our data formatting steps.
- **Classification Models** from Sklearn Library (Logistic Regression, Tree, SVM, ...)
- **K-Fold Cross Validation, Grid Search** (Parameter Tuning), and **Feature Selection** algorithms.
***

## 1. Introduction

In today's market, many companies have a mobile presence. Often, these companies provide free products/services in their mobile apps in an attempt to transition their customers to a paid membership. For this, you need a Budget. Since marketing efforts are never free, these companies need to know exactly who to target with offers and promotions.

- **Market:** The target audience is customers who use a company's free product. In this case study, this refers to users who installed (and used) the company's free mobile app.

- **Product:** The paid memberships often provide enhanced versions of the free products already given for free, alongside new features.

- **Goal:** The objective of this model is to predict which users will not subscribe to the paid membership so that greater marketing efforts can go into trying to "convert" them to paid users.
***

## 2. Business Challenge
- In this Case Study, we will be working for a fin-tech company that wants to provide its customers with a paid mobile app subscription that will allow them to track all of their finances in one place. To attract customers, the company releases a free version of its app with some of the main features unlocked.


- The company has tasked you to identify which users will most likely NOT enroll in the paid product so that additional offers can be given to them. Because of the costs of these offers, the company does not want to offer them to everybody, especially customers who were going to enroll anyways.
****
