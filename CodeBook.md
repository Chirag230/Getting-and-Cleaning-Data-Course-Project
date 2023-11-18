List of the original data sets inside the downloaded zip file:
 - 'README.txt': describes about the general information and background related to the data sets within the zip file.

 - 'features_info.txt': Shows information about the variables used on the feature vector.

 - 'features.txt': List of all features.

 - 'activity_labels.txt': Links the class labels with their activity name.

 - 'train/X_train.txt': Training set.

 - 'train/y_train.txt': Training labels.

 - 'test/X_test.txt': Test set.

 - 'test/y_test.txt': Test labels.

	 - 'train/subject_train.txt':   Each row identifies the subject who performed the activity for each window sample.
        Its range is from 1 to 30. (for training set)

 - 'test/subject_test.txt':  Each row identifies the subject who performed the activity for each window sample.
    Its range is from 1 to 30. (for test set)
  
  The following data sets are not been used in the current project. 

 - 'train/Inertial Signals/total_acc_x_train.txt'; 'train/Inertial Signals/body_acc_x_train.txt';
   'train/Inertial Signals/body_gyro_x_train.txt'. More information related to these three data sets can be
    found in 'README.txt', 'feature_info.txt' and 'feature.txt' and the original website.


Data Set Information:
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities
(WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its
embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.
The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets,
where 70% of the volunteers was selected for generating the training data and 30% the test data.

About variables:
x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.
features contains the correct names for the x_data dataset, which are applied to the column names stored in
