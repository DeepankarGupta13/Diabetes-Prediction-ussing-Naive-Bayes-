# Diabetes-Prediction-using-Naive-Bayes-
#Introduction
Naïve Bayes approach can be used to make the essentials of good health practices
accessible to everyone. It will help patients by guiding them to predict diabetes using the
symptoms provided by the user. The system will comprise of a symptom data set which is
further categorized as Name, Attributes, and Record data. Based on the ranking of each
symptom provided, the diagnosed result suggests the possibility of the person suffering
from diabetes.
Diabetes is a chronic disease, with numerous cases enrolled annually. The number of deaths
caused by diabetes has been expanding each year, and it is crucial to anticipate the factor so
that they can be relieved at the soonest guaranteeing the patient's life is saved. This
prediction is effectively acquired by utilizing Naïve Bayes Classifier. This algorithm classifies,
based on the indications of whether an individual has diabetes or not.
Naïve Bayes algorithm is a supervised learning algorithm, which is based on Bayes theorem
and used for solving classification problems.
This section describes the experimental results obtained after training Multinomial and
Gaussian Naïve Bayes Classifiers on the diabetes patient dataset. The purpose of these
experimental results is for performance evaluation of two classifier and to recommend the
best algorithm suited for prediction. In machine learning, a Confusion Matrix is used to
analyze the performance of the classification algorithm. The Confusion matrix is a tabular
structure where the rows represent Actual class and columns represents Predicted class.
Naïve Bayes has numerous real world applications
Real time Prediction: Naive Bayes is an eager learning classifier and it is sure fast. Thus, it
could be used for making predictions in real time.
Multi class Prediction: This algorithm is also well known for multi class prediction feature.
Here we can predict the probability of multiple classes of target variable.
Text classification/ Spam Filtering/ Sentiment Analysis: Naive Bayes classifiers mostly used in
text classification (due to better result in multi class problems and independence rule) have
higher success rate as compared to other algorithms. As a result, it is widely used in Spam
filtering (identify spam e-mail) and Sentiment Analysis (in social media analysis, to identify
positive and negative customer sentiments)
Recommendation System: Naive Bayes Classifier and Collaborative Filtering together builds a
Recommendation System that uses machine learning and data mining techniques to filter
unseen information and predict whether a user would like a given resource or not.

#Background:
The Naïve Bayes algorithm is comprised of two words Naïve and Bayes,
Which can be described as:
Naïve: It is called Naïve because it assumes that the occurrence of a certain feature is
independent of the occurrence of other features. Such as if the fruit is identified on the bases
of color, shape, and taste, then red, spherical, and sweet fruit is recognized as an apple.
Hence each feature individually contributes to identify that it is an apple without depending
on each other.
Bayes: It is called Bayes because it depends on the principle of Bayes' Theorem.
Bayes' theorem:
In probability theory, it relates the conditional probability and marginal probabilities of two
random events.
It is a way to calculate the value of P(B|A) with the knowledge of P(A|B).
Bayes' theorem allows updating the probability prediction of an event by observing new
information of the real world.
Example: If cancer corresponds to one's age then by using Bayes' theorem, we can determine
the probability of cancer more accurately with the help of age.
Bayes' theorem can be derived using product rule and conditional probability of event A with known event B:
As from product rule we can write:
1. P(A ⋀ B)= P(A|B) P(B) or
Similarly, the probability of event B with known event A:
1. P(A ⋀ B)= P(B|A) P(A) 
Equating right hand side of both the equations, we will get:
![image](https://user-images.githubusercontent.com/86234577/128301382-60c27b76-5b69-4fd5-8ba5-6230f6cdb697.png)

The above equation (a) is called as Bayes' rule or Bayes' theorem. This equation is basic of
most modern AI systems for probabilistic inference.
It shows the simple relationship between joint and conditional probabilities. Here,
P(A|B) is known as posterior, which we need to calculate, and it will be read as Probability of
hypothesis A when we have occurred an evidence B.
P(B|A) is called the likelihood, in which we consider that hypothesis is true, then we calculate
the probability of evidence.
P(A) is called the prior probability, probability of hypothesis before considering the evidence
P(B) is called marginal probability, pure probability of an evidence.
In the equation (a), in general, we can write P (B) = P(A)*P(B|Ai), hence the Bayes' rule can be written as:

![image](https://user-images.githubusercontent.com/86234577/128301418-7c7d5026-ad22-44cb-98cb-029341272a31.png)

Where A1, A2, A3,........, An is a set of mutually exclusive and exhaustive events.
Working of Naïve Bayes' Classifier:
Working of Naïve Bayes' Classifier can be understood with the help of the below example:
Suppose we have a dataset of weather conditions and corresponding target variable "Play".
So using this dataset we need to decide that whether we should play or not on a particular
day according to the weather conditions. So to solve this problem, we need to follow the
below steps:
1. Convert the given dataset into frequency tables.
2. Generate Likelihood table by finding the probabilities of given features.
3. Now, use Bayes theorem to calculate the posterior probability.
It is easy and fast to predict class of test data set. It also perform well in multi class
prediction.
When assumption of independence holds, a Naive Bayes classifier performs better
compare to other models like logistic regression and you need less training data.It perform
well in case ofcategorical input variables compared to numerical variable(s). For numerical
variable, normaldistribution is assumed (bell curve, which is a strong assumption).
Dataset used:
The Pima Indian Diabetes (PID)
dataset having: 9 = 8 + 1 (Class Attribute) attributes, 768 records
describing female patients (of which there were 500 negative instances
(65.1%) and 268 positive instances (34.9%)). The detailed description
of all attributes is given in Table 1.
Our methodology consists of three steps which are explained below
![image](https://user-images.githubusercontent.com/86234577/128301495-a78f9522-68f9-474b-bd34-3a623c5d2df7.png)

