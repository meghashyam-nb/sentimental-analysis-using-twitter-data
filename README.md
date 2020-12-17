# sentimental-analysis-using-twitter-dataThis script can tell you the sentiments of people regarding to any events happening in the world by analyzing tweets related to that event. It will search for tweets about any topic and analyze each tweet to see how positive or negative it's emotion is. 

Getting Started
First of all login from your Twitter account and goto Twitter Apps. Create a new app (How to create twitter app) and goto Keys and access tokens and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later.

Installation
Download or Clone the repo, Navigate to the directory containing the files and run

python setup.py install
or if you have different versions of python installed then

python3 setup.py install 
to install the dependencies.

Usage
Once you have created an app on twitter and installed all the dependencies by running setup.py, open main.py and paste your Consumer Key, Consumer Secret, Access Token and Access Token Secret. After that save and run the script. You will be prompted to enter the keyword/hashtag you want to analyze and the number of tweets you want to analyze. Once the analysis is completed, a pie chart will be generated disclosing the results of analysis.

Built With
Python 3.6
tweepy
textblob
matplotlib
Contributing
Fork it
Create your feature branch: git checkout -b my-new-feature
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request

Authors
Meghashyam

License
This project is licensed under the  Apache License 2.0- see the LICENSE.md file for details
