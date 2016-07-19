Code book
The script run_analysis.R executed the step 5 for making the tidy data set
.	As a first step it reads the data imported to the folder
.	The names for the columns were assigned.
.	Merging the data was performed
.	Reading the data from the test data performed
.	Again the merging of the data performed for the test data
.	Then the test data and training data are combined
.	Finally, the tidy data set was generated.The final data set are printed in the file called tidydata.txt
Variables
.	xtrain, ytrain, xtest, ytest, subjectTrain and subjectTest contain the data from the  files.
.	testdata merge the previous datasets to further analysis.
.	features contains the correct names for the xdata dataset, which are applied to the column names stored  
.	Similar approach is taken with activity names through the activitytype variable.
.	Trainingdata merges xtrain,ytrain  in a big dataset.
.	Finally, finaldata contains the relevant averages and the tidy data are stored in the tidydata.txt
