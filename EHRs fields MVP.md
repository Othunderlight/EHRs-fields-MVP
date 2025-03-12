## EHRs System Requirements - MVP version
### Overview
This document outlines the UI fields for an Electronic Health Records (EHRs) system, including support for e-prescriptions.

## UI Fields for Each User

### Doctor's UI

#### home page
- **patient name**
- **last visit record DATE**
- **all patient info BUTTON -> LIST**
- **nfc id number**
- **all Current Medications LIST**
  - filtered by:
    - OTC
    - current treatement
    - other doctors: filtered by doctor's specilization

- **medical report history:** 
  - by this doctor
  - by others
    - filtered by doctor specilization


- **create new report BUTTON:** 
  - visit date - end date (still active option)
  - **icd number for this specific condition**
  - **condition name**
  - Medical History for this specific condition/treatment
  - Allergies that happen for this specific condition/treatment
    - the old Allergies
    - the new Allergies
  - **Lab Results for this specific condition/treatment:**
    - old Lab Results
    - new Lab Results
  - **Current Medications:**
    - all past (stoped) Medicines history 
    - past (stoped) medicines for this specific condition/treatment 
    - Current medicines for this specific condition/treatment
    - other current medicines 
    - **prescripe new Medicine BUTTON:**
    
      - add medicine button
      - checkbox: if the medicine may make addiction in the long term
      - e force check box: if the medicine make addiction
      - Drug Interactions alert  

  - observations  
  - notes 

 



### Pharmacist's UI
- **Patient name**
- **nfc id number**
- **is smoking**
- **is regnant/... if women**
- **Family Medical History**
- **Allergies BUTTON -> LIST**
- **medications**
  - **all Current Medications LIST**
    - filtered by:
      - OTC
      - chronic 
  - **past OTC medications**
 
- **Prescription Management:**
  - check for ePrescription: coming from the doctor
  - new OTC prescription: Drug Interaction Alerts



### Patient's UI
- **Personal Dashboard:**
  - all info 
  - active treatements
    - Medical Records report: from each doctor
  - Medications: 
    - current medicines for each treatement
    - just OTC
    - chronic

- **Health Information:**
  - Allergies
  - Current Medications + current medicines for each
  - ABO 
 


## Patient Information

### Demographics
- **Name:** First, Middle, Last
- **Date of Birth (Age)** + for chiildren age in monthes + weight
- **Gender**
- **Marital Status** (Single, Married, Divorced, Widowed)
- **Military Status** (Active, Veteran, None)
- **id number or/plus nfc**
- **ABO**

### Contact Information
- **Address:** Street, City, State
- **Phone Number(s)**
- **Emergency Contact:** Name, Relationship, Phone Number

### situation
- **habits: smoking, sport...**
- **pregnancy - ارضاع**  if woman

### Medical Information
- **Medical History:** check it down
- **Allergies:** Medication, Food, Environmental
- **Current Medications:** Prescription, Over-the-Counter, Supplements
- **Immunization Records** - **Family Medical History**



## Medical History:
- started date - end date (still active option)
- **Medication:** (illnesse/condition) name
  - ex: Chronic Condition, non Chronic Condition 
  - icd number for the diseis (check bilal docs)
- **Medical Records reports** for this specific condition 
- **medicines:** filtered and ordered by medical records
  - past medicines

    - this condition
    - related condition

  - current medicines

    - this condition
    - related condition
    - another conditions
    - just OTCs or Supplements

- Allergies that happen
    - the old Allergies
    - the new Allergies

      - this condition
      - related condition

- **Lab Results**
    - old Lab Results
    - new Lab Results

      - this condition
      - related condition
  
- **Previous Surgeries**
- observations  
- notes


## Medical Report 
  - visit date - end date (still active option)
  - **icd number for this specific condition**
  - **condition name**
  - Medical History for this specific condition/treatment
  - Allergies that happen for this specific condition/treatment
    - the old Allergies
    - the new Allergies
  - **Lab Results for this specific condition/treatment:**
    - old Lab Results
    - new Lab Results
  - **Current Medications:**
    - all past (stoped) Medicines history 
    - past (stoped) medicines for this specific condition/treatment 
    - Current medicines for this specific condition/treatment
    - other current medicines 

  - observations
  - notes 


## Doctor/Pharmacist Prescription
  - medicine name
    - comercial name
    - scientefic name/substance

  - pharmaticual form  

  - medicine dosage (عيار)
  - جرعة
    - ex: twice a day, how much? ex: 2 pills at ones...
    - any specific time: ex before bed, after eating, with eating...
    - for how long: ex 10 monthes, 3 weeks....

  - other info: auto filled by salem
    - starting date
    - ending date
    - patient name
    - age: adult, pediatric, geriatric
    - prescriber info:
      - doctor:
        - name
        - specilization
        - phone number
        - clinic/hospital 
          - name
          - location
          - phone number

      - pharmacist:
        - name
        - phone number
        - pharmacy
          - name
          - location
          - phone number