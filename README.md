# ICD-to-CCS-Pneumonia-Inpatient-Patients
This code takes a patients medical history (ICD codes in past episodes) and created appx 35 clinical conditions that predict a patient being readmitted to a hospital after treatment for Pneumonia.
There are 13 .do files that map patient diagnosis ICD codes to clinical conditions. The files are labelled file1_pnr1_cc.do to file13_pnr1_cc.do 
The stata log file Predicting_Readmission_Scores_Patients_HeartAttack_HRRP.txt shows how I use these clinical conditions and other covariates to predict a patient's likelihood
of returning back to the hospital after discharge. In this specific example, I predict the probability of a readmission following a discharge for a heart attack (AMI)
patient. 
