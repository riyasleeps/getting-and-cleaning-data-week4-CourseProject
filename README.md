# getting-and-cleaning-data-week4-CourseProject
Project Overview

The Coursera Getting and Cleaning Data course project aims to process data collected from the accelerometer and gyroscope of a Samsung Galaxy S smartphone, ultimately creating a tidy dataset suitable for later analysis. 

- README.md: This file offers a detailed overview of the dataset and the steps involved in its creation.
- tidy_data.txt: The resulting dataset, containing cleaned and processed data.
- CodeBook.md: A document explaining the dataset's contents, including variables and the transformations used to generate it.
- run_analysis.R: An R script utilized to generate the dataset.

Study Design
The source data originates from the Human Activity Recognition Using Smartphones Data Set. It comprises data from 30 volunteers, aged 19-48, who wore a Samsung Galaxy S II smartphone on their waist while performing six activities. The smartphone's accelerometer and gyroscope captured 3-axial linear acceleration and angular velocity at a constant rate of 50Hz. Data labeling was manually performed from video recordings.
Preprocessing involved noise filtering and sampling in fixed-width sliding windows. Features were extracted from time and frequency domains. Subsequently, training and test data were merged, and mean and standard deviation measurements were extracted, resulting in 79 variables. Finally, a tidy dataset was created by averaging each variable for each activity and subject.

Creating the Dataset
The run_analysis.R script was pivotal in creating the dataset. It performed the following tasks:
- Downloaded and unzipped the source data.
- Merged training and test sets.
- Extracted mean and standard deviation measurements.
- Descriptively named activities and appropriately labeled variables.
- Generated an independent tidy dataset with averages for each activity and subject.
- Wrote the dataset to tidy_data.txt.













