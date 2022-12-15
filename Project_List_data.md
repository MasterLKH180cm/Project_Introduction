# Li, Guo-Hung's Data Projects
---
# Project List
---
[TOC]
<!---
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
 --->
## DeepDRG
### Advisor
Dr. Jim long, AESOP tech
### Project introduction
Using **GRU** model with patient's medicine record, procedure record, operation record and problem list to **suggest proper main diagnosis code**.
### Target
**Speed up the coding diagnosis from minutes to seconds** and improve the accuracy of coding.
### Contribution
1. Collect 15 years Urology and Chest Medicine inpatients' data.
2. Data modeling and evaluation.
3. Get **over 80% in precision**

---
## NTU MED GOD, LIFESTYLE GROUP
### Advisor
Prof. Fei-Pei Lai, principal investigator of Medical Informatics Laboratory  
Dr. Jung-Yien Chien, pulmonologist in Mational Taiwan University Hospital

### Project introduction
Dashboards of wearable devices data for medical caregivers to observe patients' health condition.
### Target
Build a complete system and apply to more medical research.
### Contribution
1. Develop and maintain of subject data monitoring platform 
    - UI/UX
    - Database management
    - Bash script writing
    - Data fetching for medical research
2. Collect lifestyle data, environmental data, and concatenate with a clinical questionnaire
3. **Prediction of acute exacerbation of COPD in 7 days**
4. Get **over 80% in accuracy** without clinical questionnaire
5. Prove that lifestyle data could be as important as a clinical questionnaire in disease prediction

---
## ESTABLISHING A MACHINE-LEARNING MODEL BASED ON PERIOPERATIVE DATA TO PREDICT AND PREVENT ANESTHESIA-RELATED ADVERSE OUTCOMES

### Collaborator
Dr. Pei-Fu Chen, anesthesiologist at Far Eastern Memorial Hospital
### Project introduction
Establish a **risk predicting model** to reduce the risks of post-anesthesia **mortality and morbidity** when assessing patients in a pre-anesthesia clinic.
### Target
Reduce the mortality and morbidity of patients.
### Contribution
1. Data cleaning, outlier removing, extreme imbalanced data preprocessing (400:1)
2. Features include demography data, lab data, medical history, vital sign, and departments
3. Modeling with machine learning 
4. Performance evaluation
5. Visualization
6. Deployment
7. Get **over 50% in F1-score** when predicting the mortality rate
8. Get over 40% F1-score when predicting the risk of 5 common complications 
---

## ENHANCED PREDICTION OF MORTALITY IN CRITICALLY ILL PATIENTS BY COMBINING MACHINE LEARNING MODELS: A THREE-STEP STRATEGY AND PREDICTED RISK-STRATIFIED ANALYSIS
### Collaborator
Dr. Yu-Chang Yeh
### Project introduction
Build an AI prediction model of mortality and length of stay. 
### Target
Reduce the mortality and morbidity of patients by paying more attention on patients in higher risk.
### Contribution
1. Data cleaning
2. Feature engineering
3. Modeling with machine learning
4. Get **over 80% in accuracy, 90% in AUROC, and 60% in F1-score**
5. Prediction performance is better than APACHE II and APACHE IV
---
## ONSET DATE EXTRACTION FOR STROKE PATIENT
### Collaborator
Associate Prof. Pei-Fang Tang
### Project introduction
Extract the onset date of stroke patients and their NIH Stroke Scale (NIHSS) from the admission summary.
### Target
Reduce more than 30% of the time for clinical caregivers to survey medical records. 
### Contribution
1. Data cleaning
2. Use **regular expression** to filter out the sentences without date-alike strings.
3. Use **LSTM** to vote if the reserved data contains the onset date or not.
4. Get **over 80% in accuracy**
---
## PHYSICAL ACTIVITY LEVEL IDENTIFICATION
### Advisor
Prof. Chia-Tai Chan, principal investigator of Ubiquitous Computing Laboratory
### Project introduction
To monitoring user's daily activity levels, I had developed an **Android App** to collect user's demography data and acceleration data. Then I modeling these data with **machine learning models** and compare the performance.
### Contribution
1. App development
2. Data collection
3. Feature engineering
4. Modeling with machine learning
5. Get **over 90% in accuracy**
6. Submit Conference paper and it has been adapted

---
## LATERALIZATION OF WOMEN’S BRAIN CHANGE WITH AGE
### Advisor 
Prof. Yu-Te Wu, principal investigator of Medical Image and Signal Analysis Laboratory
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