# Li, Guo-Hung's Projects
---
# Project List
---
[TOC]

## Establishing machine-learning model based on perioperative data to predict and prevent anesthesia-relate adverse outcomes

### Collaborator
Dr. Pei-Fu Chen
### Project introduction
This project aims to establish a risk predicting model, which can be embed into PAER, IAER, and EMR
for practicing. Anesthesiologist can know post-anesthesia mortality and morbidity risks in more detail when assessing patients in pre-anesthesia clinic, and make a plan to reduce these risks. It also helps communicate with patients and manage medical resources. This project can develop a model for medical decision making system and lead to a more personal, more accurate, and more intelligent medical care.
### Contribution
1. Data cleaning, outlier removing, extreme imbalanced data preprocessing (400:1)
2. Features include demography data, lab data, medical history, vital sign, and departments
3. Modelling with machine learning 
4. Performance evaluation
5. Visualiation
6. Deployment
7. Get over 50% in F1-score when predicting the mortality rate
8. Get more then 40% F1-score when predicting the risk of 5 common complications 
---

## EMERGENCY & CRITICAL CARE ICU PROJECT
### Collaborator
Dr. Yu-Chang Yeh
### Project introduction
The mean age of critically ill patients admitted to ICU is steadily increasing, and these patients have higher morbidity and mortality. In addition, these patients may have more complications and require advanced treatments. ANZICS (Australian and New Zealand Intensive Care Society) has built an ICU database, names as CORE APD, and recruited an international collaboration with 13 countries. Our team has helped the TSCCM (Taiwan Society and Critical Care Medicine) and TSECCM (Taiwan Society of Emergency and Critical Care Medicine) to build Taiwan CORE database, and we have recruited 16 hospitals to join this program. The first step of this project is to build an AI prediction model of mortality and length of stay using the data from this database. 

### Contribution
1. Data cleaning
2. Feature engineering
3. Modelling with machine learning
4. Get over 80% in accuracy, 90% in AUROC, and 60% in F1-score
5. Prediction performance is better than APACHE II and APACHE IV
---
## PHYSICAL THERAPY OF STROKE
### Collaborator
Associate Prof. Pei-Fang Tang
### Project introduction
This project aims to automatically extract the onset date of stroke patents and their NIH Stroke Scale (NIHSS) from admission summary. It could reduce more than 30% of time for clinical caregivers to survey the medical records. 
### Contribution
1. Data cleaning
2. Use regular expression to filt out the sentences without date-aliked strings.
3. Use LSTM to vote if the reserved data contains onset date or not.
4. Get over 80% in accuracy.
---
## NTU MED GOD, LIFESTYLE GROUP
### Advisor
Prof. Fei-Pei Lai, principal investigator of Medical Informatics Laboratory

### Project introduction
With the rapid progress of medicine, a lot of treatments and medications have been developed,
and the relationship between lifestyle and diseases have being also elucidated. Precision
medicine, is regarded as to provide the best treatment plan for each individual patient. At
present, most precision medicine research is based on historical data of electronic medical
records to develop related applications. When the patient is discharged from hospital, lifestyle
and environmental risks still affect the disease control. However, these factors are currently difficult to effectively collect and use for analysis. This project aims to collect these factors from patients suffered from different disease and build prediction model for patients and doctors to improve the quality of medical care.
### Contribution
1. Develop and mentain of subject data monitoring platform 
    - UI/UX
    - Database management
    - Data fetching for medical research
2. Collect lifestyle data, environmental data, and concatenate with clinical questionnaire
3. Prediction of acute exacerbation of COPD in 7 days
4. Get over 80% in accuracy without clinical questionnaire
5. Prove that lifestyle data could be as important as clinical questionnaire in disease prediction
---
## PHYSICAL ACTIVITY LEVEL IDENTIFICATION
### Advisor
Prof. Chia-Tai Chan, principal investigator of Ubiquitous Computing Laboratory
### Project introduction
In order to monitoring user's daily activity level, I had developed an Android App to collect user's demography data and acceleration data. Then I modelling these data with machine learning models and compare the performance.
### Contribution
1. App development
2. Data collection
3. Feature engineering
4. Modelling with machine learning
5. Get over 90% in accuracy
6. Submit Conference paper and it has been adapted

---
## LATERALIZATION OF WOMEN’S BRAIN CHANGE WITH AGE
### Advisor 
Chao-Wen Huang and Prof. Yu-Te Wu, principal investigator of Medical Image and Signal Analysis Laboratory
### Project introduction
The lateralization of brain function refers to some neural functions, or cognitive processes tend to be more dominant in one hemisphere than the other. The project is to find out the relation between age and the change of lateralization pattern.
### Contribution
1. Use 100 females' T1 images with cortical surface extraction and curvature_based alignment.
  
2. Use 5 features of brain structure include:
    - fractal dimension(FD)
    - segment thickness
    - local gyrification index(LGI)
    - surface area
    - volume  

3. Calculate lateralization index as (R-L)/(R+L).  
4. Calculate pearson correlation coefficients for their lateralization index and ages.
