# spam_filter
Building my first spam filter from scratch with a Naive Bayes algorithm and testing its accuracy!

## Table of Contents
- General Information
- Setup
- Usage
- Project Results
- Future Data Exploration Ideas
- Contact

## General Information
I’m uploading the code of the spam filter I built!

The goal was to build a Naive Bayes algorithm from scratch to filter spam emails in mail inboxes. Our main aim was to reach an accuracy of 80%, and we managed to overachieve that! I extracted the data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/228/sms+spam+collection) to carry out my analysis!📈 The dataset is made of 5,572 SMS messages that are already classified by humans. This helps the algorithm learn how to calculate the spam probability of new messages!

## Setup
First off, make sure you have conda🐍👀:

`conda create -n <replace-with-name-you-want> python=3.11`

`conda activate <replace-with-name-you-want>`

`pip install -r requirements.txt`

## Usage
Check out the `spam_filter.ipynb` file in my repo to see how I've extracted, cleansed, explored, analysed the data, and built the Naive Bayes spam detector! 

## Project Results
The spam filter had an accuracy of 89.96% on the test set, which is a good result not for production, but only for such an easy method as the Naive Bayes! We initially aimed for an accuracy of over 80%, but we managed to do way better than that!

## Future Data Exploration Ideas
We could try to make the program more robust in its prediction by making it more sensitive to letter case, punctuations, and keywords!

## Contact
For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on LinkedIn too! Happy coding!💻
