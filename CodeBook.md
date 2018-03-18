## Code Book
This code book describes the data used in this project for the resulting tidy data set.

### Files used

For the purpose of this project, the files in the Inertial Signals folders were not used. The files that were used to load data are listed below:

* test/subject_test.txt
* test/X_test.txt
* test/y_test.txt
* train/subject_train.txt
* train/X_train.txt
* train/y_train.txt

### Variables

From the related files, we can see:

* Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
* Values of Varible Subject consist of data from “subject_train.txt” and "subject_test.txt"
* Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
* Names of Varibles Features come from “features.txt”
* Levels of Varible Activity come from “activity_labels.txt”

### Identifiers

* Subjet: The ID of the test subject.
* Activity: The type of activity performed when the corresponding measurements were taken.

### Measurements

Names of Features were labelled using descriptive variable names.

* Prefix t is replaced by time
* Acc is replaced by Accelerometer
* Gyro is replaced by Gyroscope
* Prefix f is replaced by frequency
* Mag is replaced by Magnitude
* BodyBody is replaced by Body

### Activity labels

* Walking (value 1): Subject was walking during the test.
* Walking_upstairs (value 2): Subject was walking up a staircase during the test.
* Walking_downstairs (value 3): Subject was walking down a staircase during the test.
* Sitting (value 4): Subject was sitting during the test.
* Standing (value 5): Subject was standing during the test.
* Laying (value 6): Subject was laying down suring the test.


