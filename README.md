# Getting-and-Cleaning-Data-Course-Project

#### Step 1: Loading Data
I begin by loading the data from the UCI HAR Dataset. There are separate sets for training and testing, covering features, activity labels, and subject information. I also read in the feature descriptions and activity labels.

#### Step 2: Setting Column Names
To make the data more understandable, I assign specific names to columns in each dataset. For instance, the feature datasets get labeled with descriptive feature names, while the activity and subject datasets get clear identifiers.

#### Step 3: Merging Data
After naming columns, I merge the training and testing datasets, bringing together the feature data with their corresponding subjects and activities. This unified dataset is crucial for further analysis.

#### Step 4: Subsetting Relevant Columns
I then identify the columns that are particularly useful for our analysis—those related to activities, subjects, mean, and standard deviation. I create a subset of the data that contains only these relevant columns for further processing.

#### Step 5: Transforming Data
Here, I make the dataset more informative by merging in descriptive activity names. After that, I aggregate the data to create a second tidy dataset. This new dataset contains the averages of each variable for each activity and subject, arranged neatly for analysis. Finally, I save this tidy dataset into a text file for future reference.

This script basically takes raw data, organizes it, adds clarity to the columns, filters out unnecessary information, and creates a tidy dataset that's more manageable and suitable for in-depth analysis.
