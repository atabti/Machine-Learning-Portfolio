# Quora Insincere Questions Classification


## General Description:

In this competition you will be predicting whether a question asked on Quora is sincere or not.

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

Has a non-neutral tone
Has an exaggerated tone to underscore a point about a group of people
Is rhetorical and meant to imply a statement about a group of people
Is disparaging or inflammatory
Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
Makes disparaging attacks/insults against a specific person or group of people
Based on an outlandish premise about a group of people
Disparages against a characteristic that is not fixable and not measurable
Isn't grounded in reality
Based on false information, or contains absurd assumptions
Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers
The training data includes the question that was asked, and whether it was identified as insincere (target = 1). The ground-truth labels contain some amount of noise: they are not guaranteed to be perfect.

Note that the distribution of questions in the dataset should not be taken to be representative of the distribution of questions asked on Quora. This is, in part, because of the combination of sampling procedures and sanitization measures that have been applied to the final dataset.

## Data fields:

* qid - unique question identifier
* question_text - Quora question text
* target - a question labeled "insincere" has a value of 1, otherwise 0

## Content:

[Credit Card Fraud Detection](https://github.com/atabti/Data_Science_Portfolio/blob/master/Credit%20Card%20Fraud%20Detection/Credit%20Card%20Fraud%20Detection.ipynb) ![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/44px-Jupyter_logo.svg.png)


If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at amokrane.tabti@gmail.com.
