# Machine-learning-
Admission_Prediction using Linear Regression
The dataset contains several parameters which are considered important during the application for Masters Programs. The parameters
included are : 1. GRE Scores ( out of 340 ) 2. TOEFL Scores ( out of 120 ) 3. University Rating ( out of 5 ) 4. 
Statement of Purpose and Letter of Recommendation Strength ( out of 5 ) 5. Undergraduate GPA ( out of 10 ) 6. 
Research Experience ( either 0 or 1 ) 7. Chance of Admit ( ranging from 0 to 1 )
This dataset was built with the purpose of helping students in shortlisting universities with their profiles. 
The predicted output gives them a fair idea about their chances for a particular university.
Problem definition: The dataset gives the idea of various parameters for admission in B-schools.
But they are not able to identify as to which parameters are important so they can focus on it. so we need to identify the features highly 
correlated to our possibility of admission.
 Solution: First we import the entire dataset and try 
 I have tried to eliminate the variable or features which are not significant for students to get admission.
 We have use Backward elimination method and eliminated the features based on their p values greater than 0.05 as we have 
 considered it to be as our level of significance.
 And as a result the model has eliminated University rating as a parameter of selection. 
All other parameters are important for admission.
