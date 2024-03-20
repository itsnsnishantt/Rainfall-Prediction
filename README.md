# Rainfall-Prediction-using-Machine-Learning

Libraries used:-
Pandas – used for data analysis.
Use the required data only
Removes noise or irrelevant data
Numpy – used for mathematical calculations (uses numpy arrays).

Reads the excel file data in a table format.
 // Excel file – historical data
Performs data cleaning
Removes the unnecessary columns. Since, for rainfall prediction we use data like evaporation, humidity, sunshine, daily temperature (maximum and minimum). 
Removing data – date, sea level pressure and so on.
Output = cleaned data

Reads the cleaned data
Now we train the model using the cleaned data. 
We use a predefined model for training i.e., Scikit’s linear regression model which is present sklearn library.
In order to reduce complexity, we convert the data into 2d vector format (since the data was in array format or matrix).

Linear regression
Linear regression – predicts the value of a variable(independent variable) using another variable(dependent variable).
In our project,
dependent variable = cleaned data variable 
independent variable = user input (temperature, pressure etc)

Output
The o/p will be in graphical form in order to achieve that we import matplotlib (used for static, animation and interactive visualization).
Specifically, we use pyplot library from matplotlib.
In the graph, x – axis denotes the days and y – axis denotes the temperature, pressure etc. 
In short, if the temperature and humidity is high it is expected to heavy rain otherwise it can be mid-level and so on.
