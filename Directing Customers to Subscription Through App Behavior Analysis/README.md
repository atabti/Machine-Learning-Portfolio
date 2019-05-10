# Directing customers to subscription through app behavior analysis

## Project Overview:

In today's market, many companies have a mobile presence. Often, these companies provide free products/services in their mobile apps in an attempt to transition their customers to a paid membership. Some examples of paid products, which originate from free ones, include YouTube Red, Pandora Premium, Audible Subscription and You Need a Budget. Since marketing efforts are never free, these companies need to know exactly who to target with their offers and promotions.
    - Market: The target audience is customers who use a company's free product. For this project, this refers to users who installed (and used) the company's free mobile app.
    - Product: The paid memberships often provide enhanced versions of the free products already given for free, alongside new features. For example, YouTube Red allows you to leave the app while still listening to a video.
    - Goal: The objective of this model is to predict which users will not subscribe to the paid membership, so that greater marketing efforts can go into trying to "convert" them to paid users.

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
