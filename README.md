# Evaluation-Of-Academic-performances

1.Introduction:

Student’s academic success is evaluated by their performance in exams conducted by the institute or universities.
So here,evaluation of academic performance project evaluates the marks of different subjects of students to get the desire result to report weather the student performance is good or not.
Academic performance/achievement is the extent to which a student,teacher,or institution has attained their short or long term educational goals and is measured either by continuous assessment or cumulative grade point average(CGPA).
The purpose of the school or academic performance is to achive an educational goal,learning.
In the regard there are several components of the complex unit called performance.The academic performance evaluation (APE) is the annual assessment of the student’s status in their degree.
There are some things which are included in students performance, these include your grades,awards,competitive results and experiences that demonstrate your academic performance,engagement in student life.
Anything that you have completed such as a online course certification or standardized test also potentially an achievement.
The major drawback of this project is if it evaluate wrong performance then it lead to showing wrong result of students.
From the study it was found that, some noticeable side effects of assessment are suffering from self-inferiority complex, losing self-confidence , disregard for school and teachers, attempt of hurting them , selectin wrong paths, increase of competitive behaviour etc. 

2.Problem Statement:

Evaluating academic performance of students using machine learning
One of machine learing technique that can be used to evaluate the performance of the student 
Random Forest Regression 
Random forest is a supervised learning algorithm that uses an ensemble learning method for classification and regression. 
Random forest is a bagging technique and not a boosting technique. The trees in random forests run in parallel, meaning is no interaction between there trees while building the trees.
Random forest operates by constructing a multitude of decision trees at traning time and outputting the class that’s and mode of the classes(classification) or mean prediction (regression) of the individual trees.

It is one of the most accurate learning algorithms available. For many data stes, it produces a highly accurate classifier.

•	It is one of the most accurate learning algorithms available. For many data sets, it produces a highly accurate classifier.
•	It runs efficiently on large databases


This project is made through python language where libraries used here to:

•	Pandas ( for data manipulation and analysis )
•	Matplotlib (for visualization)
•	Seaborn (That uses Matplotlib underneath to plt graphs. It will be used to visualize random distributions.)

3.Methodology :

Step 1:
●	Import pandas as pd
●	Import matplotlib as plt
Step 2: Loading the dataset of Student Performance with the help of pandas 

Step 3:Showing the info of the dataset with help of info() function.

Step 4:Storing the different columns of object datatype and showing on the screen

Step 5: Using unique() function to store the values of different columns of object datatypes

Step 6: Checking the dataset not have null values with help of isnull() function.

Step 7: Using graph to check the gender is balanced or not

Step 8:Plotting  the graph of preparation course took part in it.

Step 9:Calculating out the average score from different subject scores.

Step 10:Plotting out the graph between several labels 

Step 11: Creating the dictionaries for different column whose datatype is object. 

Step 12:Replacing the datatypes of object to int datatypes

Step 13:Importing train_test_split from sklearn.model_selection

Step 14: Testing data size of 25 percent with random state is 2

Step 15: Importing RandomForestRegressor 

Step 16: Using fit() having train dataset of x and y

Step 17: Predicting the marks of the students

Step 18:Showing the prediction arrays
 
Step 19: Importing r2_score from sklearn.metrics

Step 20: Printing out the prediction accuracy on the screen.

4.Result and Discussion:
Using the following model we can predict the marks

5.Conclusion:
There are many things have to be done to achieve academic success. Firstly, it is connected with knowing oneself as a personality. Because once you understand yourself, it is well become clear which points you should work on and improve.
This system overcome many limitations incorporated in attendance, this system saves a great amount of time and reduces errors which may occur during attendance calculation. 
The system I have developed is fully responsive which can be used in mobile, tablets and different operating systems. Some other benefits are, 
 Automated and web-based for easy accessibility 
 It is a dynamic and flexible system 
 It excludes paperwork and the possibility of making mistakes while using paper for taking attendance 
 It is very user friendly and handy 
 The records of current and previous can be available in prompt and an immediate.








