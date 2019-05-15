# Minimizing Churn Rate Through Analysis of Financial Habits

## Introduction:

Subscription Products often are the main source of revenue for companies across all industries. These products can come in the form of a ‘one size fits all' overcompassing subscription, or in multi-level memberships. Regardless of how they structure their memberships, or what industry they are in, companies almost always try to minimize customer churn (a.k.a. subscription cancellations). To retain their customers, these companies first need to identify behavioral patterns that act as catalyst in disengagement with the product.

* Market: The target audience is the entirety of a company's subscription base. They are the ones companies want to keep.

* Product: The subscription products that customers are already enrolled in can provide value that users may not have imagined, or that they may have forgotten.

* Goal: The objective of this model is to predict which users are likely to churn, so that the company can focus on re engaging these users with the product. These efforts can be email reminders about the benefits of the product. especially focusing on features that are new or that the user has shown to value.

## Business Challenge:

The data comes from a fintech company that wants to provide its customers with a paid mobile app subscription that will allow them to track all their finances in one place. To attract customers, the company releases a free version of their app with some of the main features unlocked.
We will identify which users will most likely NOT enroll in a paid product, so that additional offers can be given to them. Due to the costs of these offers, the company does not want to offer them to everybody, especially customers who were going to enroll anyways.

## Data Overview:

We have access to the each customer's app behaviour data. This data allows us to see the date and time of app installation, as well as the features the user engaged with in the app. App behaviour is characterised as the list of app screens the user looked at and whether the user played the financial mini-games available.
The app usage data is only from the user's first day in the app. This limitation exists because users can enjoy a 24-hour free trial of the premium features and the company wants to target them with new offers shortly after the trial is over.
The data fields we'll be working with are as follows:
* first_open: The datetime when the user first opened the app
* dayofweek: the integer day of the week when the user first opened the app. Starts at 0, which is Sunday and runs to 6 which is Saturday.
* hour: Hour of the day when user first opened app. in 24 hours format as 18:00:00. Correlates with dayofweek.
* age: Age of the user.
* screen_list: Comma-seperated list of screens that the users accessed in their first 24 hours.
* numscreens: The number of screens accessed in their first 24 hours.
* liked: Each screen has an feature to 'like' that particualr screen. If any screens are liked, this value will be 1, otherwise 0.
* minigame: 1 if the user played the mini-game, 0 otherwise.
* used_premium_feature: 1 if the user accessed any of the premium features in the first 24 hours, 0 otherwise.
* enrolled: 1 if the user enrolled, 0 otherwise. This is the field that will be predicted later.
* enrolled_date: If the user enrolled at any time, this value is popopulated with the date of enrollment.

## Content:

[Directing customers to subscription through app behavior analysis](https://github.com/atabti/Data_Science_Portfolio/blob/master/Directing%20Customers%20to%20Subscription%20Through%20App%20Behavior%20Analysis/Directing%20Customers%20to%20Subscription%20Through%20App%20Behavior%20Analysis.ipynb) ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/44px-Jupyter_logo.svg.png)


If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at amokrane.tabti@gmail.com.
