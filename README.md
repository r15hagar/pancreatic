# pancreatic
Capstone / Pancreatic Tool
Project overview and goals:
The goal of this project is to identify and evaluate the best classification model for
detecting individuals at risk for developing pancreatic cancer, as well as what features,
such as biomarkers or patient information have strong importance in driving the models. I
will be training and tuning binary classification models to classify a patient as susceptible
or not susceptible to developing pancreatic cancer. The data references urinary biomarker
levels such as LYVE1, REG1A, TFF1, CA19-9 which will help to define feature importance as
well as show trends.

Expected Results
Once preprocessing and EDA are complete, the key features (biomarkers) most strongly
associated with pancreatic cancer will be identified through LASSO regression. Following
feature selection, the machine learning model (such as Logistic Regression or Random
Forest) will predict whether a patient is likely to develop pancreatic cancer. Cross-
validation will ensure the model’s stability, and model evaluation metrics (precision,
accuracy, F1-score) will give insights into its predictive power. The best-case scenario is a
highly accurate model that can reliably predict a patient’s likelihood of developing
pancreatic cancer, which could be used for early intervention.

Rationale, why is this question important?
Pancreatic cancer is one of the deadliest cancers, with a 5-year survival rate of less than
10% due to late diagnosis. Each year, about 60,000 people are diagnosed in the U.S., and
over 90% of patients die within a year of diagnosis. Early detection is critical to improving
survival rates, but current methods are often invasive or unreliable. This model aims to
provide a non-invasive, cost-eVective solution by predicting cancer risk based on urinary
biomarkers, which could enable earlier diagnosis and treatment.

From a business perspective, the healthcare industry could use such a model to develop
new diagnostic tools or improve existing ones, potentially reducing healthcare costs
associated with late-stage cancer treatments. Pharmaceutical companies could also
benefit by identifying at-risk individuals for clinical trials. Additionally, insurers could use
such models to better assess patient risk and improve preventive care strategies,
ultimately leading to better health outcomes and reduced costs.
