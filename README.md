# EVBV-Insurance-Eligibility
This chatbot predicts insurance claim eligibility using a trained Random Forest model. It accepts structured patient data via text or voice, processes it through a machine learning pipeline, and returns a binary prediction: eligible or not eligible.

This data frame contains the following columns:

age : age of policyholder
sex: gender of policy holder (female=0, male=1)
bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 25
steps: average walking steps per day of policyholder
children: number of children / dependents of policyholder
smoker: smoking state of policyholder (non-smoke=0;smoker=1)
region: the residential area of policyholder in the US (northeast=0, northwest=1, southeast=2, southwest=3)
charges: individual medical costs billed by health insurance
insuranceclaim: yes=1, no=0

Objective:
Understand the Dataset & cleanup (if required).
Build classification model to predict weather the insurance will be claimed or not.
Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.
