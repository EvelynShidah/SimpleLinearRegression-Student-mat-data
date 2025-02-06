This data approach student achievement in secondary education of two Portuguese schools. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. 
Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por). In Cortez and Silva, 2008, the two datasets were modeled under binary/five-level classification and regression tasks. 
Important note: the target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. 
It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful (see paper source for more details).

Explore the data and find out the answers for the following questions:

Is there a relationship between studytime and grades? How strong is that relationship?
Is there a relationship between traveltime and grades? How strong is that relationship?
What is the relationship between studytime & traveltime, and grades?
Given a studytime and/or traveltime, can the grades be predicted?

Exercise
By using the student_mat.csv as the data, apply logistic regression model and observe the classification report. Use studytime , travel, G1 and G2 as the features or X.

Note: categorize the G3 as a nominal variable, where

G3 >= 10 --> Pass
G3 < 10  --> Fail
