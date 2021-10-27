# Working-with-DataScience
Working With Naive Bayes and Linear Regression

Part 1: Using Naïve Bayes to work with Text Data
#Representing text as data 
#.Given a simple dataset

#simple_train = ['call you tonight', 'Call me a cab', 'please call me... PLEASE!']
#Learn the 'vocabulary' of the training data: convert text into a matrix of token counts.
#Transform training data into a 'document-term matrix' (which is a sparse matrix).

#Print the sparse matrix.

#Convert the sparse matrix to a dense matrix (Tip: you can use “toarray()”)
#Examine the vocabulary and document-term matrix together

#Transform testing data into a document-term matrix (using existing vocabulary)
#       use the test data as:
#       simple_test = ["please don't call me"]

#Examine the vocabulary and document-term matrix together



PART B: Analyzing SMS Data with Naive Bayes
#Read into the data from the file “sms.tsv”; give the names of columns as ['label', 'message']; and print the first 10 samples to view part of the data.
#Convert label to a numeric variable.

#Then define the X and y

#Split into training and testing sets by train_test_split(); and print the shape of training set and test set.

#Use the two Naïve Bayes models (GaussianNB and MultinomialNB) to finish the following requirements, respectively:

#calculate accuracy of predictions
#give the confusion matrix
#print message text for the false positives
#print message text for the false negatives

PART 2: LINEAR REGRESSION:

#The Data: import load_boston from sklearn.datasets 

#The Goal: Using Linear Regression on the dataset

#The Tasks:

#1.  First, read into the data and process it in the right format for using machine learning.

#2. Then, use the DataFrame corr() method to show what features are correlated with each other.

#3. The columns don't have any labels. Given the name of columns as ['crim', 'zn', 'indus', 'chas', 'nox', 'rm', 'age', 'dis', 'rad', 'tax', 'ptratio', 'b', 'lstat']; then use the DataFrame corr() again.

#4. Now, you have the numbers from the correlation matrix, but it's not as easy to view or interpret as a plot. Please write codes to plot correlations by color same as (similar with) the following figure
