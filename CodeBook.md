Code Book for Coursera Getting and Cleaning Data Course Project
Data
The tidy_data.txt file is a space-separated text file. It contains averaged signal measurements for subjects and activities.
Variables
-subject: Integer identifier (1-30).
-activity: String identifier (WALKING, etc.).
Measurements
All measurements are normalized within [-1, 1].
Time-domain Signals
- Mean and standard deviation of body acceleration and gravity acceleration.
- Mean and standard deviation of body acceleration jerk and angular velocity jerk.
- Mean and standard deviation of magnitude for various signals.
Frequency-domain Signals
- Mean and standard deviation of body acceleration and jerk.
- Weighted average of frequency components.
- Mean, standard deviation, and weighted average of magnitude.
Transformations
- Merged training and test sets.
- Extracted mean and standard deviation measurements.
- Replaced activity identifiers with descriptive names.
- Renamed variables to be descriptive.
- Created a new data set with averages of variables for each activity and subject.
The run_analysis.R script executed these transformations