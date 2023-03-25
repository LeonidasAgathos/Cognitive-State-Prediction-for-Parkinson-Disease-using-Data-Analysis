## Prognostic-factors-and-prediction-of-Parkinson-s-disease

### The problem
In this particular project, the main topic we dealt with is Parkinson's disease. Parkinson's disease is a degenerative disorder of the central nervous system.
which is quite widespread nowadays, as it is estimated that 1% of the population of the population over 65 suffer from the disease.
The initial symptoms of the disease are stiffness, tremor and slowness of movement, while a later stage usually includes
dementia and depression. The subject we focused on in this research, is the cognitive state of a patient, i.e. the deterioration of
of the disease in that particular patient. The prediction of the state of deterioration of a
patient is an important fact, as the early prediction of an upcoming deterioration,can greatly assist the physician in charge in order, through medication, to
delay this otherwise inevitable process.

### Our approach
The target of the project, was to predict the possibility of a patient moving to the next, worse cognition state. Our target 
class was "Cognitive State" and we took the next meet with the doctor, after the Baseline meeting. For the rest of the data, we used Baseline, so we can predict the 
second, worse state, using the data from the first meet with a doctor. The final dataset we used for our experiment, we had to merge the different datasets 
containing different questions of patients. We used SQL Server to merge the different files and we extracted a dataset in which we could apply the preprocess techniques.
We finally took the final dataset and cleaned it,filled it and filtered it using Python. To extract our final model, we used SMOTE to balance the data 
and we applied RUSBoost Classifier, AdaBoost Classifier and XGB Classifier with the first two algorithms achieving the best Precision. For any further information, feel 
free to contact us.
CoAuthor @AndreasAvgou
