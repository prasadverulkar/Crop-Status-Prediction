# Crop-Status-Prediction

### Crop Status
There are only a few techies who are working on projects related to Agriculture. It is very important
for us to contribute equally to different sectors when it is required all over the world. Though the old
techniques of agriculture cannot be ignored, we need to think of adding innovative technology on
top of them.

### Goal: 
Given the dataset related to agriculture, you should be able to build a model that will classify
the status of the existing crop by considering a set of parameters.

### Data Description:
Data is recorded by considering parameters related to crop when it is treated with toxicants(pesticides).

### Attribute Information:
1. ID - Unique number represents each record
2. Insects - Average number of insects that (may) affect the crop.
3. Crop - Type of crop [Food crop and Feed crop]
4. Soil - Type of soil [Clay and silt]
5. Category_of_Toxicant - Values 1, 2, 3 represent three different toxicants available in the market.
6. Does_count - Represents the dosage count of toxicants.
7. Number_of_Weeks_Used - Represents the number of weeks for which the crop remained
toxicant.
8. Number_Weeks_does_not used - Represents the number of weeks that the toxicants are used on
the crop.
9. Season - Represents the various seasons (Monsoon, etc.,)
10. Crop_status - 0 represents ‘Crop can be used further’, 1 represents ‘crop is damaged due to
nature’, 2 represents ‘toxicants
are responsible for crop’s damage’.

### Provided Files:
training_data: This file consists of all the features. It should be used for both training and model
validation purposes. [80,000 records]
test_data: Test file consists of all attributes except the target variable and prediction is to be made
for all the rows in the test file. [35,000 records]
Sample_Submission: This file is an example of how the solution file is to be created.

### Objective Of The Problem: 
The objective of the problem is to predict the status of the crop which
will be helpful for agriculture experts.

### Evaluation Criteria: 
The metric of evaluation for the problem is Accuracy score.

Hint: Try creating new features using existing attributes.
Note: Prediction should be made against every record on test data
