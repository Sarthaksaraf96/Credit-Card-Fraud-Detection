<h1 align="center"> Credit-Card-Fraud-Detection </h1>


<h2> Introduction </h2>
we will use various predictive models to see how accurate they  are in detecting whether a transaction is a normal payment or a fraud. As described in the dataset, the features are scaled and the names of the features are not shown due to privacy reasons. Nevertheless, we can still analyze some important aspects of the dataset.


<h2> Our Goals: </h2>
<ul>
<li> Understand the little distribution of the "little" data that was provided to us. </li>
<li> Create a 50/50 sub-dataframe ratio of "Fraud" and "Non-Fraud" transactions</li>
<li> Use Logistic Regression Classifiers we are going to use and Check accuracy. </li>
</ul>


<h2> Outline: </h2>
I. <b>Understanding our data</b><br>
a) Gather Sense of our data<br><br>

II. <b>Preprocessing</b><br>
a) Scaling and Distributing<br>
b) Splitting the Data<br><br>

III. <b>Oversampling</b><br>
a) Distributing and Correlating<br>
b) Oversampling with SMOTE<br><br>

IV. <b>Testing </b><br>
a) Testing 

<h2> Conclusion </h2>

1) The logistic regression model, after applying SMOTE for dealing with class imbalance, achieved good performance in terms of accuracy and recall for the minority class. 

2) However, the precision for the minority class is low, indicating a high number of false positives.
Further optimization of the model or exploration of other models could potentially improve the performance, especially in terms of precision for the minority class.

4) It's also important to consider the business context and the cost associated with false positives and false negatives when evaluating the model's performance.

