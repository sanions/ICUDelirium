# ICUDelirium
Predictive Modeling of Deliriousness in the Intensive Care Unit

Excessive doses and varieties of medications and drugs, constant distractions, lack of
sleep, and underlying health conditions in patients in the Intensive Care Unit contribute to their
vulnerability to deliriousness. However, ICU delirium is a condition that is often inadequately
diagnosed and neglected, but it has recently been recognized as a significant contributor to
morbidity and mortality in the ICU. In this research, de-identified ICU data from MIT’s MIMIC-
III database, including patient demographics, vital sign measurements, laboratory test results,
procedures, medications, and caregiver notes, was utilized to create a machine learning model to
predict a patient’s likelihood for becoming delirious. Delirium was diagnosed using related
diagnoses in the records, such as mental disorders and withdrawal-related conditions, and
analyzing clinical notes for related keywords established in previous studies. The features
considered in the model were based on previously determined risk factors, including drug types
(opioids, benzodiazepines, steroids, deep sedation, anticholinergics), comorbidities (especially
ion and metabolic disorders), and abnormal lab values. A random forest classifier was used to
create the predictive model which currently has a 64.8% accuracy, 0.637 precision score, and
0.613 recall score. With more features and hyperparameter tuning, a more accurate model
(currently under research) can be employed in ICUs as guidance for doctors in outlining their
treatment plan and adjusting conditions for patients, in order to reduce the probability of
delirium. The prediction model can also be key in identifying the most prominent causes of
delirium and refine existing delirium tests, such as the CAM-ICU.


The cleaned dataset used for analysis is masterFinal.csv. The main analysis is conducted in PredictionModels.ipnyb. 
