![image](https://github.com/kmcneil901/Sapient-Case-Study/assets/139075900/77eb5dd4-7ca0-4eb5-9bd3-28678ad0cb7d)
# Sapient Data Science Test Project

Kendall McNeil, January 2024

In a public health study, participants were enrolled from communities for physical exams, blood tests, and were followed up for years with disease outcomes. We are interested in investigating blood biomarkers for a prevalent and detrimental disease – diabetes. The primary focus of this project is to determine whether an individual will develop diabetes over the course of the study (incident_diabetes = 1) or not (incident_diabetes = 0). The project aims to identify the blood biomarkers associated with the development of diabetes out of data for 10,000 blood biomarkers of 8,148 study participants, constituting a binary classification problem. 

![image](https://github.com/kmcneil901/Sapient-Case-Study/assets/139075900/953ad40a-d803-49f3-a4af-1ff85122ac38)

After exploring a logistic regression model and K-Nearest Neighbors model, the strongest machine learning model at this very introductory exploration appears to be the logistic regression model (hyperparameters = fit_intercept=True, C=.1, solver='liblinear', max_iter=100) at 92% accuracy on the training set and 91% on the testing set. A gridsearch was used to identify optimal parameters. 

In this project, I have conducted an analysis considering three common alpha values: 0.05, 0.01, and 0.001. The selection of the appropriate p-value is contingent upon the stakeholder's objectives and is recommended to be determined in collaboration with an individual possessing deeper domain knowledge of blood biomarkers. My aim was to present all relevant information, providing the stakeholders with the flexibility to choose based on field expectations. From researching online, it appears .05 and .01 are the most common for this type of project question.

![image](https://github.com/kmcneil901/Sapient-Case-Study/assets/139075900/ce17d333-662a-4091-aa38-48d21b78ee02)

