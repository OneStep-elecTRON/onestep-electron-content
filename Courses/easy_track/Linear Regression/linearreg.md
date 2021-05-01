# Linear Regression

The term "regression" means "coming back to the average". <br> 
Regression Analysis is a mathematical measure to determine the average relationship between two or more variables in terms of original units of data. In regression analysis, we have two types of variables: Dependent variable (target/output variable) and independent variable (predictor/input variable). The variable whose value is to be predicted is called dependent variable whereas the variable which is used for prediction is called independent variable. <br>
Simple linear regression is defined as Y=aX+b, where , Y is dependent variable and X is independent variable. a and b are coefficients which we'll understand below by a simple example.<br>
Let us assume that marks scored by a student in exams is only related to number of hours he studied. We went to a class and collected data on marks scores and hours studied of various students. This data is represented by blue dots in the figure below. 

<p align="center">
<img src="https://github.com/Anjali001/onestep-electron-content/blob/main/Courses/easy_track/Linear%20Regression/regress.jpg" alt="drawing" width="700"/>
</p>

The straight line (red color) is called best fit line or regression line. It is called best fit because the error between the predicted values and the observed values is minimum for this line. Now, as we can see that a student can score 25 marks , even if they doesn't study at all. This is called intercept or the value of "b". You can also see that with increase in hours of study, marks increase (shown by green arrows). The value of "a" in the equation represents change in units of Y per unit of X, thus , "a" is the slope of the best fit line. As we know, slope of line is (y2-y1)/(x2-x1). Thus, a => (95-70)/(15-10) = 5 . Thus , equation bceomes Y = 5X+ 25 . So, now with any value of X, we can find a value of Y. For example, when X=1, Y would be 30. This is how we are able to establish a mathematical relationship between 2 variables, which can be used for predictive purposes. <br><br>
The above explanation was for a simple linear regression. But in real life, we have a large number of independent variables which are used to predict value of the dependant variable. Mathematically, 
Y = a1X1 + a2X2 + a3X3 + a4X4 +.....+ anXn + b














Linear Regression is the most famous machine learning algorithm and its a statistical method to carry out redictive analysis. But before we jump into understanding Linear regression, lets understand what's regression. <br/>

Majority of the machine learning algorithms fall under the supervised learning category. It is the process where an algorithm is used to predict a result based on the previously entered values and the results generated from them. Suppose we have an input variable ‘x’ and an output variable ‘y’ where y is a function of x (y=f{x}). Supervised learning reads the value of entered variable ‘x’ and the resulting variable ‘y’ so that it can use those results to later predict a highly accurate output data of ‘y’ from the entered value of ‘x’. A regression problem is when the resulting variable contains a real or a continuous value. It tries to draw the line of best fit from the data gathered from a number of points.</br>

Now we know a gist of what's going on in Linear Regression, lets quickly understand its working.
Let’s look at a scenario where linear regression might be useful: losing weight. Let us consider that there’s a connection between how many calories you take in and how much you weigh; regression analysis can help you understand that connection. Regression analysis will provide you with a relation which can be visualized into a graph in order to make predictions about your data. For example, if you’ve been putting on weight over the last few years, it can predict how much you’ll weigh in the next ten years if you continue to consume the same amount of calories and burn them at the same rate.<br/>

The goal of regression analysis is to create a trend line based on the data you have gathered. This then allows you to determine whether other factors apart from the amount of calories consumed affect your weight, such as the number of hours you sleep, work pressure, level of stress, type of exercises you do etc. Before taking into account, we need to look at these factors and attributes and determine whether there is a correlation between them. Linear Regression can then be used to draw a trend line which can then be used to confirm or deny the relationship between attributes. If the test is done over a long time duration, extensive data can be collected and the result can be evaluated more accurately. <br/>

<p align="center">
<img src="https://github.com/OneStep-elecTRON/ContentSection/blob/main/Courses/easy_track/Linear%20Regression/Linearreg-1.png" alt="drawing" width="700"/>
</p>

The best fit line is considered to be the line for which the error between the predicted values and the observed values is minimum. It is also called the regression line and the errors are also known as residuals. <br/>

There are some technical terminologies that would be ver necessary to get the in-depth knowledge about the algorithm but for now, we have understood how exactly the algorithm works and we will be taking a look at the other things in the other tracks where we also learn how  to optimize all the algorithms. <br/>
