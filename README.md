# Bayes
Bayes’ theorem establish that the posterior probability (the probability of an event given the new information received) is proportional to the likelihood of seeing that new information multiplied by the prior belief.  This proportionality between after data and the likelihood times the prior comes up over and over again in the machine learning. 


Formula for Bayes’ Theorem
The Bayes’ theorem is expressed in the following formula:

 

Where:
P(A|B) – the probability of event A occurring, given event B has occurred
P(B|A) – the probability of event B occurring, given event A has occurred
P(A) – the probability of event A
P(B) – the probability of event B



2. Explain the significance of Bayes theorem and for what type of problems it is helpful.

Bayes' rule is used in various occasions including a medical testing for a rare disease. With Bayes' rule, we can estimate the probability of actually having the condition given the test coming out positive. Besides certain circumstances, Bayes' rule can be applied to our everyday life including dating and friendships.

3. Explain Naive Bayes classifier and training process.

Understanding Naive Bayes and Machine Learning 


Naive Bayes algorithm falls under classification.

We can use Naive Bayes for the following things:
Face Recognition
As a classifier, it is used to identify the faces or its other features, like nose, mouth, eyes, etc.
Weather Prediction 
It can be used to predict if the weather will be good or bad.
Medical Diagnosis.

Process
Data collection
Preparing training dataset from sklearn.dataset


Transforming text data to vector space
Creating dictionary and transforming text data to vector space.

Modeling & training
Creating naive bayes classifier and training

Execute & check output
Classifying test data and printing results. 


4. Explain Email span filtering and how Bayes theorem can be helpful.

When spam filters need to classify a piece of mail, it knows that this can either be spam of not spam. Using that, the filter is able to calculate the probability of whether it believes something is spam or not. With each new incoming piece of mail that is received, there are certain words within that piece of mail, and each word has a probability of either commonly occurring in spam emails or not. The filter knows the probability that a word appears in spam mails, and by using these pieces of data, is able to calculate the probability that something is spam. With this, the filter continually updates itself with each new piece of mail it receives.
This relates to the ideas from Bayes’ theorem in class, in which we learned that you can find the probability of something occurring, the the space of another event occurring. This makes it useful to classify spam, as in the certain case that a specific word or pieces of data occur in a piece of mail, you can calculate the probability that a piece of mail in that box is spam. Then, with this, you can update your predictions based on other changing values of expectation. 

We know that Bayes Rule states that P(A|B) = [P(B|A)*P(A)] / P(B). If A is the probability that the a random piece of mail is spam, and B is the chance that the word occurs, then P(A|B) is the goal of the spam filter, which is the probability that the mail is spam given that the word exists. If the calculation occurs for each word, and also other segments of data, such as headers and HTML code, the spam filter can accurately calculate, while also updating its beliefs each time to make itself more accurate. 
We know that Bayes Rule also causes false positives and false negatives. Although these do exist, the probability of either of these occurring is quite small, as the filter is quite accurate. Even if these do occur, the predictions for the next piece of mail will always reflect these possibilities. These two articles emphasize that Bayes Theorem has many unknown applications, but is often used to help create and calculate accurate guesses. When applied to spam filtering, if you are given a piece of mail, M, Bayes Rule can be applied to determine and explain whether M’s intent is fraudulent or not, which can further justify why certain pieces of mail are put into spam, and others are not.

# REGex Software
