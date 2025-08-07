# Prediction-of-clinical-trial-success
Overview
This repository contains the code and analysis for a machine learning project focused on predicting the success of Phase 3 clinical trials. Drug development is an expensive and lengthy process, with a high rate of failure. By leveraging machine learning models and a rich dataset compiled from multiple public sources, we aim to uncover key factors that differentiate successful trials from failures. Our work provides valuable insights for pharmaceutical companies, researchers, and other stakeholders involved in the drug development pipeline.
Key Features
•	Comprehensive Dataset: We created a unique dataset by merging data from ClinicalTrials.gov, the AACT database, PubMed publications, and FDA approval records.
•	Custom Labels: We developed custom success and failure labels for over 15,000 clinical trials, addressing the lack of a standardized success metric in the source data.
•	Feature Engineering: We engineered 55 features, including operational characteristics like enrollment and retention rate, and sponsor experience in specific therapeutic areas.
•	Model Comparison: We trained and evaluated several machine learning models, including XGBoost, Random Forests, and Neural Networks, to find the most accurate predictor.
•	Actionable Insights: Our final model highlights the most important predictors of success, such as study size and retention rate, which can be used to inform trial planning and increase the likelihood of approval.
Technology Stack
•	Languages: Python
•	Libraries: pandas, scikit-learn, Keras (via SciKeras), XGBoost
•	Data Sources: ClinicalTrials.gov, AACT, PubMed, Drug@FDA
Results
Our best-performing models, XGBoost and Random Forest, achieved an accuracy of 0.84 and 0.83, respectively, and an AUC of over 0.80. The analysis showed that Enrollment and Retention Rate were the most significant predictors of trial success.

This project includes large zipped CSV files that are too big to be stored directly on GitHub.
You can download them from Dropbox using the link below:
https://www.dropbox.com/scl/fo/j40g0j4huyt200s7czmrm/AKNXgkoCW3qd4CCGrKo5ZDI?rlkey=vas6lotibh22sfrsy9f6bdvyc&st=d9hxgy64&dl=0

