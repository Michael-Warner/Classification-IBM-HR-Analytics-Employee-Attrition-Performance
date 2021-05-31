# IBM HR Analytics of Employee Attrition and Performance

## Purpose:

The purpose of this project was to correctly guess if an employee was to leave based on multiple aspects. Then to follow up with suggestions of how to reduce attrition and in turn, reduce company expenses on retraining new employees and the knock-on effect of constently losing people.

![Quit](https://media.istockphoto.com/photos/businessperson-walking-out-picture-id928080898?k=6&m=928080898&s=612x612&w=0&h=Om_wzoeaN7y-DKx5APQKVaHtb7mbOKUh403ct5M_gok=)
For a detailed analysis of this project please see code used along with the comments [here](https://github.com/Zexes9/IBM-HR-Analytics-Employee-Attrition-Performance/blob/main/Employee_Attrition_prediction.R). 

## Dataset:

The dataset is provided IBM as a fictional set of people in company. It can be found [here](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). This data set had 34 variables and one target variable, attrition.

## Method:
The methodology used was an EDA of the dataset, then to clean the dataset, run multiple classification models, lastly, to delever insights from our EDA and model analysis. 

## Result:

The best model based on recall, as we want to select all potential employees that leave, was the Gaussian Naive Bayes model. It had a recall rate of 67.6%, but still does a fair job on identifying the employees who quit from all the employees who actually did quit.
With this model, we can only be able identify 67.6% of employees who quit, the human resources department and department managers may need other measures to identify them, e.g. job performance changes or emotion.

The study also found that things that most affected the employees outcome or not was the following: 
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

## Conclusion:

It was suggested that the following measures to be implimented to improve the employees morale and to reduce their attrition rate:
 * Career counseling and coaching for new employees
 * Stock Options for junior employees
 * Working time or workload adjustment
 * Employees' caring scheme
 * Company promotion system
 * Working environment improvement
