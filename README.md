**Problem Statement**:<br>You are the data scientist at a telecom company named “Neo” whose customers
are churning out to its competitors. You have to analyze the data of your
company and find insights and stop your customers from churning out to other
telecom companies.<br>
**Customer_churn Dataset**:<br>The details regarding this ‘customer_churn’ dataset are present in the data
dictionary.<br>
**Domain**: Telecom

**Tasks To Be Performed**:<br>

**1. Data Manipulation**:
● Extract the 5th column and store it in ‘customer_5’<br>
● Extract the 15th column and store it in ‘customer_15’<br>
● Extract all the male senior citizens whose payment method is electronic
check and store the result in ‘senior_male_electronic’<br>
● Extract all those customers whose tenure is greater than 70 months or
their monthly charges is more than $100 and store the result in
‘customer_total_tenure’<br>
● Extract all the customers whose contract is of two years, payment method
is mailed check and the value of churn is ‘Yes’ and store the result in
‘two_mail_yes’<br>
● Extract 333 random records from the customer_churndataframe and store
the result in ‘customer_333’<br>
● Get the count of different levels from the ‘Churn’ column<br>

**2. Data Visualization**:<br>
● Build a bar-plot for the ’InternetService’ column:<br>
a. Set x-axis label to ‘Categories of Internet Service’<br>
b. Set y-axis label to ‘Count of Categories’<br>
c. Set the title of plot to be ‘Distribution of Internet Service’<br>
d. Set the color of the bars to be ‘orange’<br>
● Build a histogram for the ‘tenure’ column:<br>
a. Set the number of bins to be 30<br>
b. Set the color of the bins to be ‘green’<br>
c. Assign the title 'Distribution of Tenure'<br>
● Build a scatter-plot between ‘MonthlyCharges’ and ‘tenure’. Map
‘MonthlyCharges’ to the y-axis and ‘tenure’ to the ‘x-axis’:<br>
a. Assign the points a color of ‘brown’<br>
b. Set the x-axis label to ‘Tenure of customer’<br>
c. Set the y-axis label to ‘Monthly Charges of customer’<br>
d. Set the title to ‘Tenure vs Monthly Charges’<br>
e. Build a box-plot between ‘tenure’ & ‘Contract’. Map ‘tenure’ on the
y-axis &<br>
f. ‘Contract’ on the x-axis<br>
**3. Linear Regression**:<br>
● Build a simple linear model where dependent variable is ‘MonthlyCharges’
and independent variable is ‘tenure’:<br>
a. Divide the dataset into train and test sets in 70:30 ratio.<br>
b. Build the model on train set and predict the values on test set<br>
c. After predicting the values, find the root mean square error<br>
d. Find out the error in prediction & store the result in ‘error’<br>
e. Find the root mean square error<br>
**4. Logistic Regression**:<br>
● Build a simple logistic regression model where dependent variable is
‘Churn’ and independent variable is ‘MonthlyCharges’:<br>
a. Divide the dataset in 65:35 ratio<br>
b. Build the model on train set and predict the values on test set<br>
c. Build the confusion matrix and get the accuracy score<br>
d. Build a multiple logistic regression model where dependent variable
is ‘Churn’ and independent variables are ‘tenure’ and
‘MonthlyCharges’<br>
e. Divide the dataset in 80:20 ratio<br>
f. Build the model on train set and predict the values on test set<br>
g. Build the confusion matrix and get the accuracy score<br>
**5. Decision Tree:**<br>
● Build a decision tree model where dependent variable is ‘Churn’ and
independent variable is ‘tenure’:<br>
a. Divide the dataset in 80:20 ratio<br>
b. Build the model on train set and predict the values on test set<br>
c. Build the confusion matrix and calculate the accuracy<br>
**6. Random Forest:**<br>
● Build a Random Forest model where dependent variable is ‘Churn’ and
independent variables are ‘tenure’ and ‘MonthlyCharges’:<br>
a. Divide the dataset in 70:30 ratio<br>
b. Build the model on train set and predict the values on test set<br>
c. Build the confusion matrix and calculate the accuracy<br>
