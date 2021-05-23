# Linear Regression

There are mainly three types of algorithms in Machine Learning namely: Supervised, Unsupervised and Reinforcement. Since, Linear Regression is a Supervised Machine Learning algorithm , we'll focus on that for this topic. <br/>

Supervised Machine Learning means that the algorithm is first trained on the labelled dataset (train data) to form a model. After this, the machine is provided with a new set of data (test data) to the acquired knowledge to predict the outcomes. For instance, when all of us were babies, our parents told us what is a cow, rabbit, snake, squirrel etc.. (Trained us). After that, whenever we saw an animal (test data), we were able to classify it depending on our knowledge. This is Supervised Learning. <br/>

Supervised ML algorithms are of 2 types: <br/>
1. Classification: In this output variable is a category (Categorical target variable) <br/>
2. Regression: In this output variable is a value (Continuous target variable) <br/>

Let's talk about regression now. <br/>

The term "regression" means "coming back to the average". <br/> 

Regression Analysis is a mathematical measure to determine the average relationship between two or more variables in terms of original units of data. In regression analysis, we have two types of variables: Dependent variable (target/output variable) and independent variable (predictor/input variable). The variable whose value is to be predicted is called dependent variable whereas the variable which is used for prediction is called independent variable. <br/>

Simple linear regression is defined as Y=aX+b, where , Y is dependent variable and X is independent variable. a and b are coefficients which we'll understand below by a simple example.<br/>

Let us assume that marks scored by a student in exams is only related to number of hours he studied. We went to a class and collected data on marks scores and hours studied of various students. This data is represented by blue dots in the figure below. 

<p align="center">
<img src="https://github.com/Anjali001/onestep-electron-content/blob/main/Courses/easy_track/Linear%20Regression/regress.jpg" alt="drawing" width="700"/>
</p>

The straight line (red color) is called best fit line or regression line. It is called best fit because the error between the predicted values and the observed values is minimum for this line. Now, as we can see that a student can score 25 marks , even if they doesn't study at all. This is called intercept or the value of "b". You can also see that with increase in hours of study, marks increase (shown by green arrows). The value of "a" in the equation represents change in units of Y per unit of X, thus , "a" is the slope of the best fit line. As we know, slope of line is (y2-y1)/(x2-x1). Thus, a = (95-70)/(15-10) = 5 . Thus , equation becomes Y = 5X+ 25 . So, now with any value of X, we can find a value of Y. For example, when X=1, Y would be 30. This is how we are able to establish a mathematical relationship between 2 variables, which can be used for predictive purposes. <br/><br/>

The above explanation was for a simple linear regression. But in real life, we have a large number of independent variables which are used to predict value of the dependent variable. 

Mathematically, 
<p align="center">
<img src="https://github.com/Anjali001/onestep-electron-content/blob/main/Courses/easy_track/Linear%20Regression/LR_formulae.jpg" alt="drawing" width="700"/>
 </p>
<br/>

Now, we have learnt the mathematical statistics part behind linear regression, let's move forward to learn how this is used in Machine Learning. First go through linear regression algorithm from scratch to learn, how linear regression works behind the scene. Once you've completed it, move on to the second link provided below to see how you can simply import linear regression from Sklearn library and use it in your data with 2-3 simple lines of code. <br/>
 
Want to know how to implement linear regression algorithm from Scratch, Follow this link: https://colab.research.google.com/drive/1-q7YKL852EHdiNheQSXATmfBynjqT_7Y?usp=sharing
<br/>

Check this link to see how to use linear regression algorithm using Sklearn Library: https://github.com/Anjali001/GRIP_Tasks/blob/master/Linear_Regression.ipynb
<br/>
