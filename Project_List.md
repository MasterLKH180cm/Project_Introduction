# Li, Guo-Hung's Projects
---
# Project List
---
[TOC]
## 6 minutes walking test image system
### Advisor
Prof. Fei-Pei Lai, principal investigator of Medical Informatics Laboratory  
Dr. Jung-Yien Chien, pulmonologist at National Taiwan University Hospital

### Project introduction
6 minutes walking test is an important clinical test in assessing aerobic capacity and endurance. A patient is asked to walk back and forth through  a 30 meters hallway in 6 minutes, and a professional caregiver needs to stay next to the patient during the test. This system aims to make patients have the ability to conduct the test outside the hospital without accompanied by a caregiver.
### Contribution
1. Use Jetson Nano and camera to fetch the real-time image of the test.
2. Use Yolo v4 to detect the patients' joints.
3. Calculate the distance and velocity the patient has walked during the test.
 
## Establishing a machine-learning model based on perioperative data to predict and prevent anesthesia-related adverse outcomes

### Collaborator
Dr. Pei-Fu Chen, anesthesiologist at Far Eastern Memorial Hospital
### Project introduction
This project aims to establish a risk predicting model, which can be embedded into PAER, IAER, and EMR
for practicing. An anesthesiologist can know post-anesthesia mortality and morbidity risks in more detail when assessing patients in a pre-anesthesia clinic, and make a plan to reduce these risks. It also helps communicate with patients and manage medical resources. This project can develop a model for the medical decision-making system and lead to more personal, more accurate, and more intelligent medical care.
### Contribution
1. Data cleaning, outlier removing, extreme imbalanced data preprocessing (400:1)
2. Features include demography data, lab data, medical history, vital sign, and departments
3. Modeling with machine learning 
4. Performance evaluation
5. Visualization
6. Deployment
7. Get over 50% in F1-score when predicting the mortality rate
8. Get more than 40% F1-score when predicting the risk of 5 common complications 
---

## EMERGENCY & CRITICAL CARE ICU PROJECT
### Collaborator
Dr. Yu-Chang Yeh
### Project introduction
The mean age of critically ill patients admitted to ICU is steadily increasing, and these patients have higher morbidity and mortality. Besides, these patients may have more complications and require advanced treatments. ANZICS (Australian and New Zealand Intensive Care Society) has built an ICU database, names as CORE APD, and recruited an international collaboration with 13 countries. Our team has helped the TSCCM (Taiwan Society and Critical Care Medicine) and TSECCM (Taiwan Society of Emergency and Critical Care Medicine) to build the Taiwan CORE database, and we have recruited 16 hospitals to join this program. The first step of this project is to build an AI prediction model of mortality and length of stay using the data from this database. 

### Contribution
1. Data cleaning
2. Feature engineering
3. Modeling with machine learning
4. Get over 80% in accuracy, 90% in AUROC, and 60% in F1-score
5. Prediction performance is better than APACHE II and APACHE IV
---
## ONSET DATE EXTRACTION FOR STROKE PATIENT
### Collaborator
Associate Prof. Pei-Fang Tang
### Project introduction
This project aims to automatically extract the onset date of stroke patients and their NIH Stroke Scale (NIHSS) from the admission summary. It could reduce more than 30% of the time for clinical caregivers to survey medical records. 
### Contribution
1. Data cleaning
2. Use regular expression to filter out the sentences without date-alike strings.
3. Use LSTM to vote if the reserved data contains the onset date or not.
4. Get over 80% in accuracy.
---
## NTU MED GOD, LIFESTYLE GROUP
### Advisor
Prof. Fei-Pei Lai, principal investigator of Medical Informatics Laboratory  
Dr. Jung-Yien Chien, pulmonologist in Mational Taiwan University Hospital

### Project introduction
With the rapid progress of medicine, a lot of treatments and medications have been developed,
and the relationship between lifestyle and diseases has been also elucidated. Precision
medicine is regarded as providing the best treatment plan for each individual patient. At
present, most precision medicine research is based on historical data of electronic medical
records to develop related applications. When the patient is discharged from the hospital, lifestyle
and environmental risks still affect disease control. However, these factors are currently difficult to effectively collect and use for analysis. This project aims to collect these factors from wearable devices and IoT devices, and build prediction models for patients who suffered from different diseases to improve the quality of medical care.
### Contribution
1. Develop and maintain of subject data monitoring platform 
    - UI/UX
    - Database management
    - Data fetching for medical research
2. Collect lifestyle data, environmental data, and concatenate with a clinical questionnaire
3. Prediction of acute exacerbation of COPD in 7 days
4. Get over 80% in accuracy without clinical questionnaire
5. Prove that lifestyle data could be as important as a clinical questionnaire in disease prediction
---
## PHYSICAL ACTIVITY LEVEL IDENTIFICATION
### Advisor
Prof. Chia-Tai Chan, principal investigator of Ubiquitous Computing Laboratory
### Project introduction
To monitoring user's daily activity levels, I had developed an Android App to collect user's demography data and acceleration data. Then I modeling these data with machine learning models and compare the performance.
### Contribution
1. App development
2. Data collection
3. Feature engineering
4. Modeling with machine learning
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

3. Calculate the lateralization index as (R-L)/(R+L).  
4. Calculate Pearson correlation coefficients for their lateralization index and ages.
