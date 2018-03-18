## Code Book
This code book describes the data used in this project and the processing to create the resulting tidy data set.

## Files used

For the purpose of this project, the files in the Inertial Signals folders were not used. The files that were used to load data are listed below:

* test/subject_test.txt
* test/X_test.txt
* test/y_test.txt
* train/subject_train.txt
* train/X_train.txt
* train/y_train.txt

## Variables

From the related files, we can see:

* Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
* Values of Varible Subject consist of data from “subject_train.txt” and "subject_test.txt"
* Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
* Names of Varibles Features come from “features.txt”
* Levels of Varible Activity come from “activity_labels.txt”

Activity, Subject and Features were used as part of descriptive variable names for data in data frame.

Names of Feteatures were labelled using descriptive variable names.

* Prefix t is replaced by time
* Acc is replaced by Accelerometer
* Gyro is replaced by Gyroscope
* Prefix f is replaced by frequency
* Mag is replaced by Magnitude
* BodyBody is replaced by Body
