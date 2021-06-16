# Text_Classification
Task was to make data frame without using inbuilt functions out of given folder with multiple text documents and write code from scratch of Naive Bayes to predict output.

# Classifier Used:
 NAIVE BAYES 
 MutinomialNB
 
# Method Used in the Process:
1. Obtain raw data from online source .
2. Loading data file to enivorment(if You are using google colab).
3. Adding stop words list manaully copying or using a link that return list for the same.
4. Fetching data from all folder(20) and storing them after avoiding the stop words.
5. Making feature out of the dict of all the words in all the pargraphs.
6. Making data frame using string data and features set.
7. Making the spilt in test and train data.
8. Implemented my own Navie Bayes.
9. Making Predictions (tweaking the hyperparameters)
10. Importing confusion matrix for score.
11. Got accuracy of about 82 %
12. Implemented standard In-Built Navie-Bayes.
13. Importing confusion matrix for score.
14. Got accuracy of 86 %
15. Saving results in csv with timestamp.

# Conclusion 
A MODEL WITH HARD-CODED NAVIE-BAYES IS ALMOST SAME (can perform better) THEN STANDARD IN-BULIT NAIVE BAYES.
