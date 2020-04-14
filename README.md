# Analyzing Heart Disease using Machine Learning techniques
A mini project on analyzing whether the patient has heart disease or not. The code is implemented in python and different classification models has been used: K –Nearest Neighbour (K-NN) , Decision Tree (DT), Naive Bayes (NB), Support Vector Machine(SVM), Logistic Regression, Random Forest to evaluate the accuracy. Data analysis, visualization and pre-processing techniques have been applied.

### Dataset:
The dataset used for this project is the Heart Disease dataset taken from UCI. The dataset contains 76 attributes, but for the project purpose I have only used 14 columns. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4.

### Attribute Information:

1.age: displays the age of the individual.

2.sex: displays the gender of the patient. 

    - 1 = male
    - 0 = female

3.chest pain type (4 values): displays the type of chest-pain experienced by the patient where,
    
     - 1 = typical angina
     - 2 = atypical angina
     - 3 = non — anginal pain
     - 4 = asymptotic

4.resting blood pressure: displays the resting blood pressure value of the patient.

5.serum cholestoral: displays the serum cholesterol in mg/dl 

6.fasting blood sugar: compares the fasting blood sugar value of the patient with 120mg/dl.

      If fasting blood sugar > 120mg/dl then : 1 (true)
      else : 0 (false)

7.resting electrocardiographic results: displays resting electrocardiographic results where,

    -0 = normal
				-1 = having ST-T wave abnormality
				-2 = left ventricular hyperthrophy

8.maximum heart rate achieved: displays the max heart rate achieved by the patient.

9.exercise induced angina: 

	-1 = yes
	-0 = no

10.oldpeak = ST depression induced by exercise relative to rest: displays the value which is an integer or float.

11.the slope of the peak exercise ST segment: 

	-1 = upsloping
	-2 = flat
	-3 = downsloping

12.number of major vessels (0-3) colored by flourosopy: displays the value as integer or float.

13.thal: displays the thalassemia where,

	-3 = normal
	-6 = fixed defect
	-7 = reversable defect

14. Diagnosis of heart disease : displays whether the patient is suffering from heart disease or not where,

		-0 = absence
		-1, 2, 3, 4 = present.
## Conclusion
I have achieved the highest accuracy for the test set for Naive Bayes and Logistic Regression thats equal to 85.25%.
