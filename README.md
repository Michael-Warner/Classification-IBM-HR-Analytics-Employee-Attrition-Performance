# IBM HR Analytics of Employee Attrition and Performance

## Purpose:

The purpose of this project was to correctly guess if an employee was to leave based on multiple aspects. Then to follow up with suggestions of how to reduce attrition and in turn, reduce company expenses on retraining new employees and the knock-on effect of constently losing people.

![Quit](https://media.istockphoto.com/photos/businessperson-walking-out-picture-id928080898?k=6&m=928080898&s=612x612&w=0&h=Om_wzoeaN7y-DKx5APQKVaHtb7mbOKUh403ct5M_gok=)

## Dataset:

The dataset is provided IBM as a fictional set of people in company. It can be found [here](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). This data set had 34 variables and one target variable, attrition.

## Method:

## Result:

## Conclusion:


In this project, we evaluate our model based on **recall(sensitivity)** as we want to know how well the model detect the employee quitted(TP) from who actually quitted (TP + FN).<br/>
It is the proportion of positive result that were correctly classified from all the actual positive.
It is more useful when the class is *imbalanced*, as true negative is not included in the calculation and thus recall is not affected the imbalance.<br/>
In this dataset, we have lots of 'No Attrition' relative to 'Yes' and we would like to predict 'Yes' (i.e leave the company) precisely.
With recall , we can evaluate the models by looking at how well they predict an actual 'Yes' from all the actual positive (True positive and false negative).<br/>

We select **Gaussian Naive Bayes** as the best model from Logistic Regression, KNN, Decision Tree and Random Forest, based on sensitivity(recall).<br/>

In short, the key findings can be found below:<br/>


## Summary   <br/>


###### Influential Factors of Attrition<br/>
Our study finds out the employees’ major concerns as following : <br/>
 1) Employees’ background <br/>
    a) Age <br/>
    b) Working experience<br/>
 2) Employees’ working conditions<br/>
    a) Working overtime<br/>
    b) Job role<br/>
    c) Job levels<br/>
 3) Employees’ benefits<br/>
    a) Salary<br/>
    b) Stock options<br/>


###### Recommendations 
 We suggest the following measures to improve the employees morale and the attrition rate :<br/>
 1) Career counseling and coaching for new employees<br/>
 2) Stock Options for junior employees<br/>
 3) Working time or workload adjustment<br/>
 4) Employees' caring scheme<br/>
 5) Company promotion system<br/>
 6) Working environment improvement <br/>
