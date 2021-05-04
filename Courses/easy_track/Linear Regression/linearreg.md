# Linear Regression

The term "regression" means "coming back to the average". <br> 
Regression Analysis is a mathematical measure to determine the average relationship between two or more variables in terms of original units of data. In regression analysis, we have two types of variables: Dependent variable (target/output variable) and independent variable (predictor/input variable). The variable whose value is to be predicted is called dependent variable whereas the variable which is used for prediction is called independent variable. <br>
Simple linear regression is defined as Y=aX+b, where , Y is dependent variable and X is independent variable. a and b are coefficients which we'll understand below by a simple example.<br>
Let us assume that marks scored by a student in exams is only related to number of hours he studied. We went to a class and collected data on marks scores and hours studied of various students. This data is represented by blue dots in the figure below. 

<p align="center">
<img src="https://github.com/Anjali001/onestep-electron-content/blob/main/Courses/easy_track/Linear%20Regression/regress.jpg" alt="drawing" width="700"/>
</p>

The straight line (red color) is called best fit line or regression line. It is called best fit because the error between the predicted values and the observed values is minimum for this line. Now, as we can see that a student can score 25 marks , even if they doesn't study at all. This is called intercept or the value of "b". You can also see that with increase in hours of study, marks increase (shown by green arrows). The value of "a" in the equation represents change in units of Y per unit of X, thus , "a" is the slope of the best fit line. As we know, slope of line is (y2-y1)/(x2-x1). Thus, a => (95-70)/(15-10) = 5 . Thus , equation bceomes Y = 5X+ 25 . So, now with any value of X, we can find a value of Y. For example, when X=1, Y would be 30. This is how we are able to establish a mathematical relationship between 2 variables, which can be used for predictive purposes. <br><br>
The above explanation was for a simple linear regression. But in real life, we have a large number of independent variables which are used to predict value of the dependent variable. 
Mathematically, 
<img src="https://github.com/Anjali001/onestep-electron-content/blob/main/Courses/easy_track/Linear%20Regression/LR_Formula.bmp" alt="drawing" width="700"/>
<br>
<br>
Want to know how to implement linear regression algorithm from Scratch, Follow this link: https://colab.research.google.com/drive/1-q7YKL852EHdiNheQSXATmfBynjqT_7Y?usp=sharing
<br>
Check this link to see how to use linear regression algorithm using Sklearn Library: https://github.com/Anjali001/GRIP_Tasks/blob/master/Linear_Regression.ipynb
<br>
