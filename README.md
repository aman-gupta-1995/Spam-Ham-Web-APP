# Spam-Ham-Web-APP

SpamHam 
 
SpamHam is a text-classification app which detects whether the message/email is spam or not. I've used Naive-Bayes along with NLP (TF-IDF, Bag of Words and more). 
In order to perform an experiment I've combined two datasets (Enron email spam/ham and SMS spam classification) into one to gather more data. See this notebook to get what I am saying. 
To check out this project in action I've deployed it on heroku Click on this link to check
 
Built With 
 
Django 2.1    
Python 3.6 
Scikit-Learn
Numpy
Pandas
Matplotlib
Seaborn
HTML5
CSS
Bootstrap-v4
Love
Installing/ Things you need to install the Web App and how to set up the project locally?

Python3
Pip
Django(2.1)
Conda
Steps

Make a virtual environment using "conda create -n envname python=3.6 pip"
source activate envname (for mac/linux) | activate envname (for windows)
pip install -r requirements.txt
Run the app using python manage.py runserver
Milestones for version 2

Implement login and tailor experience for each user
Collect the result reported by user for false classification of messages/email
Model will self-learn from the reported data
