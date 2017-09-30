# UCIML-Human-Activity-Recognition
MultiClass Classification | Model Benchmarking | ElasticNet | Preprocessed | HAR UCIML
<br>
### Introduction

The Human Activity Recognition database was built from the recordings of 30 study participants performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The objective is to classify activities into one of the six activities performed.
<br>
### Attribute information

For each record in the dataset the following is provided:
<br>
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 561-feature vector with time and frequency domain variables.
- Its activity label.
- An identifier of the subject who carried out the experiment.

### F-1 Scores Obtained

SVM - 96.5
<br>
RF - 92.7
<br>
SGDClassifer(Elastic Net Penalty) - 92
<br>
KNN (10 neighbour classifier) - 90
