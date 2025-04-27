# Instructor-led Lab: Data Reduction

In this assignment you will practice implementing data reduction techniques in Python. You will use the data in the [`calihospital.txt` file](https://github.com/UM-BGEN632/week10labs/blob/main/data/calihospital.text) provided within the `data` folder. This dataset contains responses to several surveys were emailed to a random sample of 61 hospitals.

## Context 
You currently work in the Information Systems department for a consulting firm working with the state government agency that oversees the healthcare system in California. You are part of a team charged with assessing the condition of the healthcare system in California. 

| Item | Definition |
|:---|:---|
| HospitalID | The primary key of each hospital |
| Name | The legal name of the hospital |
| Zip |	Zip code where the hospital is located |
| Website |	The url for the hospital’s website |
| TypeControl |	Indicates the primary managing entity of the hospital |
| Teaching |	Indicates teaching status |
| DonorType |	This field indicates the most prominent group of donors |
| NoFTE |	Number of full-time employees registered at the hospital |
| NetPatRev |	Net patient revenue |
| InOperExp |	Estimate of the inpatient operating costs |
| OutOperExp |	Estimate of the outpatient operating costs |
| OperRev |	Operating revenue of the hospital |
| OperInc |	Operating Income is the operating revenue less the operating expenses |
| AvlBeds |	The number of available beds in the hospital |
| Work_ID |	Primary key of the personnel |
| LastName |	The last name of the personnel |
| FirstName |	First name of the personnel |
| Gender |	Gender of the individual |
| PositionID |	The foreign key for the position held |
| PositionTitle |	The title of this position |
| Compensation |	The annual amount the position is compensated for service |
| MaxTerm |	The maximum number of years an individual can serve in this position |
| StartDate |	The beginning of service for this position |

Your supervisor would like you to perform the following tasks using Python.

## Principal Component Analysis (PCA) in Python

Open the data within Python and conduct a PCA, specifically: 

* Using the numerical columns for the hospital (7 total; not variables related to position), conduct a PCA and obtain the eigenvalues.
* Based on the eigenvalues, explain how many variables you should keep. Justify your reasoning.
* Create and display a scree plot for the same set of data.
* Based on the scree plot, how many variables should you keep? Why?

## Clustering in Python

Open the data within Python and conduct a k-means cluster analysis for the numerical data. Please conduct the following assessments:

* Choose a value of k and run your analysis. Justify your choice of k.
* Create a confusion matrix for each of the three categorical variables (e.g., `Teaching`, `TypeControl`, `DonorType`) and determine which of the three variables is the best grouping variable. Why do you think it is the best fitting?

**Save your notebook with code output and responses to the questions outlined above. Then submit your notebook for grading.**