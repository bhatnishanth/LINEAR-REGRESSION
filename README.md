# LINEAR-REGRESSION
This project is a machine learning algorithm named linear regression.This algorithm uses C language. This project uses very basic header file with which everybody is familiar.
It is a machine learning algorithm therefore inputs(datasets) and outputs (predicted values)  has to be provided and it maps the rules(algorithm) for the user.
This project is divided into 2 parts using switch case:
1) Theortical part
2) Algorithm part

# Theortical-Part
It includes the basic knowledge of linear regression and its applications.

# Algorithm-Part
It includes the algorthim. This algorithm can find out the relation between two operands.For eg, 1+1=2 ,the algorithm finds out the function of operator + and gives us the solution.
(P.S.-It can only find the function/indentity of addition, subtraction and multiplication.)

# Understanding the code
The algorithm inputs a dataset, for eg: (1,2),(3,4),(5,6); and returns a line which is suitable for the above dataset  in the form of 
Y= W1x1+W2x2+W3x3. W1,W2,W3 are weights which are randomly initialised. 
This input is represented in form of a matrix(2-D array). 
The predicted values are stored in another array. The formula is W1y1+W2y2+W3y3 .In the for loop, first the y^ i.e. is the matrix multiplication ,is calculated.
Then with respect to the predicted values, the error is calculated. The formula is (y^-y). The error is multiplied with learning rate. And at last the weights are updated.(W-(error times learning rate)).
After a number of iterations, the algorithm is ready.
At last, a  user defined function is used to mark the accuracy of the algorithm which lies  between 0 and 1 .
