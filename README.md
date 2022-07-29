# ECG-data-based-Blood-Pressure-Estimation
Our prime objective in this project is to estimate Blood Pressure (BP), Systolic Blood Pressure (SBP) and Diastolic Blood Pressure (DBP), values based on Electrocardiograph (ECG) data. We must classify the blood pressure reading into three groups (Normal, Prehypertension, and Hypertension) using the SBP and DBP values 
develop individual models for the three classes in order to predict blood pressure. The SBP and DBP values of the patient must be passed via the classification model if it has predicted that they fall into a particular class.

Used Adaboost and ANN regressor to estimate Blood Pressure (BP), SBP
and DBP, values based on ECG data
•Perform preprocessing,feature extraction and classification of data into
normal, prehypertension, and hypertension class
• Apply Adaboost and ANN regressor to estimate SBP and DBP values for
each class seperately and compare their accuracy
• Got average RMSE for SBP and DBP are 15% and 15% using Adaboost and
10% and 6% using ANN

Dataset chosen:
Open-source version of the Multi-Parameter Intelligent Monitoring in Intensive Care (MIMIC-II) waveform data-set from Physionet
Thousands of signals from 942 ICU patients hospitalized between 2001 and 2008
Transmissions have a 125 Hz sampling rate
Data set's synchronous Aorta Blood Pressure (ABP), ECG, and Photoplethysmograph (PPG) signals have been smoothed using a basic averaging filter
Signals with jarring discontinuities or unacceptably high heart rates have been eliminated
Signal blocks that displayed a significant change, those with inappropriate human blood pressure readings were also removed
