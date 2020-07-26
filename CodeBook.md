### Description of the variables from 'tidy.csv'
 
The following table describes all variables of the 'tidy.csv' data set. 
 
| Index |           Variables          |  Class  |  Range  | Description                                                                                               |
|-------|------------------------------| --------|---------|-----------------------------------------------------------------------------------------------------------|
|    1  |Subject                         | integer |  1 - 30 | Identifies the human subject.                                                                             |
|    2  |Activity                        | factor  |  1 -  6 | Identifies the activity. Labels: WALKING, WALKING UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING |
|    3  |Mean_Of_tBodyAcc-mean()-X       | numeric | [-1, 1] | Average of means for body acceleration on X axis.                                            |
|    4  |Mean_Of_tBodyAcc-mean()-Y       | numeric | [-1, 1] | Average of means for body acceleration on Y axis.                                            |
|    5  |Mean_Of_tBodyAcc-mean()-Z       | numeric | [-1, 1] | Average of means for body acceleration on Z axis.                                            |
|    6  |Mean_Of_tBodyAcc-std()-X        | numeric | [-1, 1] | Average of standard deviations for body acceleration on X axis.                              |
|    7  |Mean_Of_tBodyAcc-std()-Y        | numeric | [-1, 1] | Average of standard deviations for body acceleration on Y axis.                              |
|    8  |Mean_Of_tBodyAcc-std()-Z        | numeric | [-1, 1] | Average of standard deviations for body acceleration on Z axis.                              |
|    9  |Mean_Of_tGravityAcc-mean()-X    | numeric | [-1, 1] | Average of means for gravity acceleration on X axis.                                         |
|   10  |Mean_Of_tGravityAcc-mean()-Y    | numeric | [-1, 1] | Average of means for gravity acceleration on Y axis.                                         |
|   11  |Mean_Of_tGravityAcc-mean()-Z    | numeric | [-1, 1] | Average of means for gravity acceleration on Z axis.                                         |
|   12  |Mean_Of_tGravityAcc-std()-X     | numeric | [-1, 1] | Average of standard deviations for gravity acceleration on X axis.                           |
|   13  |Mean_Of_tGravityAcc-std()-Y     | numeric | [-1, 1] | Average of standard deviations for gravity acceleration on Y axis.                           |
|   14  |Mean_Of_tGravityAcc-std()-Z     | numeric | [-1, 1] | Average of standard deviations for gravity acceleration on Z axis.                           |
|   15  |Mean_Of_tBodyAccJerk-mean()-X   | numeric | [-1, 1] | Average of means for the jerk of body acceleration on X axis.                                |
|   16  |Mean_Of_tBodyAccJerk-mean()-Y   | numeric | [-1, 1] | Average of means for the jerk of body acceleration on Y axis.                                |
|   17  |Mean_Of_tBodyAccJerk-mean()-Z   | numeric | [-1, 1] | Average of means for the jerk of body acceleration on Z axis.                                |
|   18  |Mean_Of_tBodyAccJerk-std()-X    | numeric | [-1, 1] | Average of standard deviations for the jerk of body acceleration on X axis.                  |
|   19  |Mean_Of_tBodyAccJerk-std()-Y    | numeric | [-1, 1] | Average of standard deviations for the jerk of body acceleration on Y axis.                  |
|   20  |Mean_Of_tBodyAccJerk-std()-Z    | numeric | [-1, 1] | Average of standard deviations for the jerk of body acceleration on Z axis.                  |
|   21  |Mean_Of_tBodyGyro-mean()-X      | numeric | [-1, 1] | Average of means for angular velocity on X axis.                                             |
|   22  |Mean_Of_tBodyGyro-mean()-Y      | numeric | [-1, 1] | Average of means for angular velocity on Y axis.                                             |
|   23  |Mean_Of_tBodyGyro-mean()-Z      | numeric | [-1, 1] | Average of means for angular velocity on Z axis.                                             |
|   24  |Mean_Of_tBodyGyro-std()-X       | numeric | [-1, 1] | Average of standard deviations for angular velocity on X axis.                               |
|   25  |Mean_Of_tBodyGyro-std()-Y       | numeric | [-1, 1] | Average of standard deviations for angular velocity on Y axis.                               |
|   26  |Mean_Of_tBodyGyro-std()-Z       | numeric | [-1, 1] | Average of standard deviations for angular velocity on Z axis.                               |
|   27  |Mean_Of_tBodyGyroJerk-mean()-X  | numeric | [-1, 1] | Average of means for the jerk of angular velocity on X axis.                                 |
|   28  |Mean_Of_tBodyGyroJerk-mean()-Y  | numeric | [-1, 1] | Average of means for the jerk of angular velocity on Y axis.                                 |
|   29  |Mean_Of_tBodyGyroJerk-mean()-Z  | numeric | [-1, 1] | Average of means for the jerk of angular velocity on Z axis.                                 |
|   30  |Mean_Of_tBodyGyroJerk-std()-X   | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on X axis.                   |
|   31  |Mean_Of_tBodyGyroJerk-std()-Y   | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on Y axis.                   |
|   32  |Mean_Of_tBodyGyroJerk-std()-Z   | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on Z axis.                   |
|   33  |Mean_Of_tBodyAccMag-mean()      | numeric | [-1, 1] | Average of means for the magnitude of body acceleration.                                     |
|   34  |Mean_Of_tBodyAccMag-std()       | numeric | [-1, 1] | Average of standard deviations for the magnitude of body acceleration.                       |
|   35  |Mean_Of_tGravityAccMag-mean()   | numeric | [-1, 1] | Average of means for the magnitude of gravity acceleration.                                  |
|   36  |Mean_Of_tGravityAccMag-std()    | numeric | [-1, 1] | Average of standard deviations for the magnitude of gravity acceleration.                    |
|   38  |Mean_Of_tBodyAccJerkMag-mean()  | numeric | [-1, 1] | Average of means for the magnitude of jerk, of body accelaration.                            |
|   38  |Mean_Of_tBodyAccJerkMag-std()   | numeric | [-1, 1] | Average of standard deviations for the magnitude of jerk, of body accelaration.              |
|   39  |Mean_Of_tBodyGyroMag-mean()     | numeric | [-1, 1] | Average of means for the magnitude of angular velocity.                                      |
|   40  |Mean_Of_tBodyGyroMag-std()      | numeric | [-1, 1] | Average of standard deviations for the magnitude of angular velocity.                        |
|   41  |Mean_Of_tBodyGyroJerkMag-mean() | numeric | [-1, 1] | Average of means for the magnitude of jerk, of the angular velocity.                         |
|   42  |Mean_Of_tBodyGyroJerkMag-std()  | numeric | [-1, 1] | Average of standard deviations for the magnitude of jerk, of the angular velocity.           |
|   43  |Mean_Of_fBodyAcc-mean()-X       | numeric | [-1, 1] | Average of means for body acceleration on X axis.                                            |
|   44  |Mean_Of_fBodyAcc-mean()-Y       | numeric | [-1, 1] | Average of means for body acceleration on Y axis.                                            |
|   45  |Mean_Of_fBodyAcc-mean()-Z       | numeric | [-1, 1] | Average of means for body acceleration on Z axis.                                            |
|   46  |Mean_Of_fBodyAcc-std()-X        | numeric | [-1, 1] | Average of standard deviations for body acceleration on X axis.                              |
|   47  |Mean_Of_fBodyAcc-std()-Y        | numeric | [-1, 1] | Average of standard deviations for body acceleration on Y axis.                              |
|   48  |Mean_Of_fBodyAcc-std()-Z        | numeric | [-1, 1] | Average of standard deviations for body acceleration on Z axis.                              |
|   49  |Mean_Of_fBodyAccJerk-mean()-X   | numeric | [-1, 1] | Average of means for the jerk of the body acceleration on X axis.                            |
|   50  |Mean_Of_fBodyAccJerk-mean()-Y   | numeric | [-1, 1] | Average of means for the jerk of the body acceleration on Y axis.                            |
|   51  |Mean_Of_fBodyAccJerk-mean()-Z   | numeric | [-1, 1] | Average of means for the jerk of the body acceleration on Z axis.                            |
|   52  |Mean_Of_fBodyAccJerk-std()-X    | numeric | [-1, 1] | Average of standard deviations for the jerk of the body acceleration on X axis.              |
|   53  |Mean_Of_fBodyAccJerk-std()-Y    | numeric | [-1, 1] | Average of standard deviations for the jerk of the body acceleration on Y axis.              |
|   54  |Mean_Of_fBodyAccJerk-std()-Z    | numeric | [-1, 1] | Average of standard deviations for the jerk of the body acceleration on Z axis.              |
|   55  |Mean_Of_fBodyGyro-mean()-X      | numeric | [-1, 1] | Average of means for the jerk of angular velocity on X axis.                                 |
|   56  |Mean_Of_fBodyGyro-mean()-Y      | numeric | [-1, 1] | Average of means for the jerk of angular velocity on Y axis.                                 |
|   57  |Mean_Of_fBodyGyro-mean()-Z      | numeric | [-1, 1] | Average of means for the jerk of angular velocity on Z axis.                                 |
|   58  |Mean_Of_fBodyGyro-std()-X       | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on X axis.                   |
|   59  |Mean_Of_fBodyGyro-std()-Y       | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on Y axis.                   |
|   60  |Mean_Of_fBodyGyro-std()-Z       | numeric | [-1, 1] | Average of standard deviations for the jerk of angular velocity on Z axis.                   |
|   61  |Mean_Of_fBodyAccMag-mean()      | numeric | [-1, 1] | Average of means for the magnitude of body acceleration.                                     |
|   62  |Mean_Of_fBodyAccMag-std()       | numeric | [-1, 1] | Average of standard deviations for the magnitude of body acceleration.                       |
|   63  |Mean_Of_fBodyAccJerkMag-mean()  | numeric | [-1, 1] | Average of means for the magnitude of jerk, of body acceleration.                            |
|   64  |Mean_Of_fBodyAccJerkMag-std()   | numeric | [-1, 1] | Average of standard deviations for the magnitude of jerk, of body acceleration.              |
|   65  |Mean_Of_fBodyGyroMag-mean()     | numeric | [-1, 1] | Average of means for the magnitude of angular velocity.                                      |
|   66  |Mean_Of_fBodyGyroMag-std()      | numeric | [-1, 1] | Average of standard deviations for the magnitude of angular velocity.                        |
|   67  |Mean_Of_fBodyGyroJerkMag-mean() | numeric | [-1, 1] | Average of means for the magnitude of jerk, of angular velocity.                             |
|   68  |Mean_Of_fBodyGyroJerkMag-std()  | numeric | [-1, 1] | Average of standard deviation for the magnitude of jerk, of angular velocity.                |
|   69  |Mean_Of_fBodyAcc-meanFreq()-X   | numeric | [-1, 1] | Average of means of frequencies for body acceleration on X axis.                             |
|   70  |Mean_Of_fBodyAcc-meanFreq()-Y   | numeric | [-1, 1] | Average of means of frequencies for body acceleration on Y axis.                             |
|   71  |Mean_Of_fBodyAcc-meanFreq()-Z   | numeric | [-1, 1] | Average of means of frequencies for body acceleration on Z axis.                             |
|   72  |Mean_Of_fBodyAccJerk-meanFreq()-X  | numeric | [-1, 1] | Average of means of frequencies for the jerk of the body acceleration on X axis.          |
| 73  |Mean_Of_fBodyAccJerk-meanFreq()-Y  | numeric | [-1, 1] | Average of means of frequencies for the jerk of the body acceleration on Y axis.          |
| 74  |Mean_Of_fBodyAccJerk-meanFreq()-Z  | numeric | [-1, 1] | Average of means of frequencies for the jerk of the body acceleration on Z axis.          |
| 75  |Mean_Of_fBodyGyro-meanFreq()-X  | numeric | [-1, 1] | Average of means of frequencies for the jerk of angular velocity on X axis.         |
| 76  |Mean_Of_fBodyGyro-meanFreq()-Y  | numeric | [-1, 1] | Average of means of frequencies for the jerk of angular velocity on Y axis.         |
| 77  |Mean_Of_fBodyGyro-meanFreq()-Z  | numeric | [-1, 1] | Average of means of frequencies for the jerk of angular velocity on Z axis.         |
| 78  |Mean_Of_fBodyAccJerkMag-meanFreq()  | numeric | [-1, 1] | Average of means of frequencies for the magnitude of jerk, of body acceleration.    |
| 79  |Mean_Of_fBodyGyroMag-meanFreq()  | numeric | [-1, 1] | Average of means of frequencies for the magnitude of angular velocity.     |
| 80  |Mean_Of_fBodyGyroJerkMag-meanFreq()  | numeric | [-1, 1] | Average of means of frequencies for the magnitude of jerk, of angular velocity.       |
| 81  |Mean_Of_fBodyGyroJerkMag-meanFreq()  | numeric | [-1, 1] | Average of means of frequencies for the magnitude of jerk, of angular velocity.       |