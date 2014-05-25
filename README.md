Getting and Cleaning Data - Project - Tidy Data Set
===================

Steps for this function:
1. Read the files into dataframes.
2. Bind the columns from test data and train data.
3. Eliminate columns from the result in Step 2 which do not have "mean()" or "std()" in the column names.
4. Take the mean of observations per activity per subject.
5. Replace activity numbers with Activity names from activity_labels
6. Final step: write the .txt file


Thanks for reading!

Best,
Ted
