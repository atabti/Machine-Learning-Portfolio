# Predicting the Likelihood of E-Signing a Loan Based on Financial History

## Introduction:

Lending companies work by analyzing the financial history of their loan applicants, and choosing whether or not the applicant is too risky to be given a loan. If the applicant is not, the company then determines the terms of the loan. To acquire these applicants, companies can organically receive them through their websites/apps. often with the help of advertisement campaigns. Other times. lending companies partner with peer-to-peer (P2P) lending marketplaces, in order to acquire leads of possible applicants. Some example marketplaces include Upstart. Lending Tree, and Lending club. In this project, we are going to asses the quality of the leads our company receives from these marketplaces.

* Market: The target audience is the set of loan applicants who reached out through an intermediary marketplace.

* Product: A loan.

* Goal: Develop an model to predict for quality applicants. In this case study, quality applicants are those who reach a key part of the loan application process.

## Business Challenge:

In this Case Study we will be working for a fintech company that specializes on loans. It offers low APR loans to applicants based on their financial habits, as almost all lending companies do. This company has partnered with a P2P lending marketplace that provides real-time leads (loan applicants). The numbers of conversions from these leads are satisfactory.

The company tasks you with creating a model that predicts whether or not these leads will complete the electronic signature phase of the loan application (a.k.a. e_signed). The company seeks to leverage this model to identify less quality applicants (e.g. those who are not responding to the onboarding process). and experiment with giving them different onboarding screens.

The reason for selecting the e-signing process as the response variable is due to the structure of the loan application.

The official application begins with the lead arriving into our website after we opted to acquire it. Here, the applicant begins the onboarding process to apply for a loan. The user begins to provide more financial information by going over every screen of the onboarding process. This ﬁrst phase ends with the applicant providing his/her signature indicating all of the given information is correct.

Any of the following screens. in which the applicant is approved/denied and given the terms of the loan. is dependent on the company. not the applicant. Therefore the effectiveness of the onboarding is measured up to the moment the applicant stops having control of the application process.

## Data Overview:

Because the applicants arrived through a marketplace. we have access to their financial data before the onboarding process begins. This data includes personal information like age, and time employed, as well as other financial metrics. Our company utilizes these financial data points to create risk scores based on many different risk factors.

In this case study. we are given the set of scores from algorithms built by the finance and engineering teams. Furthermore. the marketplace itself provides us with their own lead quality scores. We will leverage both sets of scores. as well as small list of personal/financial features to predict if the user is likely to respond to our current onboarding process.

## Content:

[Predicting the Likelihood of E-Signing a Loan Based on Financial History](https://github.com/atabti/Data_Science_Portfolio/blob/master/Predicting%20the%20Likelihood%20of%20E-Signing%20a%20Loan%20Based%20on%20Financial%20History/Predicting%20the%20Likelihood%20of%20E-Signing%20a%20Loan%20Based%20on%20Financial%20History.ipynb) ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/44px-Jupyter_logo.svg.png)


If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, send me an email at amokrane.tabti@gmail.com.
