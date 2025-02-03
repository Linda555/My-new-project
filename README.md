
# VeriCare – The AI-agent that ensures healthcare professionals have legitimate access to patient records at the right time.

Final project for the Building AI course

## Summary

VeriCare is an AI-driven program that automatically calculates the probability of unauthorized access to patient records. If an access attempt is classified as "not approved," the system generates a report. The probability assessment is based on factors such as the caregiver’s department, job title, journal activity, and the patient’s most recent visits.


## Background

Each year, healthcare staff access patient records without having an active care relationship with the patient, violating patient privacy. This practice conflicts with the Patient Data Act, which states that access to medical records must be justified by patient care involvement.
While digital footprints are left when records are accessed, reviewing logs is time-consuming and not consistently enforced across all departments. As a result, patients are often left to suspect and investigate unauthorized access themselves. Legally, ensuring medical record security is the healthcare provider’s responsibility, yet in practice, the burden often falls on the patient.



## How is it used?

VeriCare monitors healthcare workers' interactions with patient records and analyzes these activities against predefined criteria. Once a month, the system generates a report for the system administrator, flagging suspicious access events. These cases are then further investigated within the relevant department.
By automating data analysis, VeriCare makes it easier to detect and manage potential violations, streamlining compliance monitoring.



<img src="ehr-g05113767b_1280.png" width="300">


## Data sources and AI methods
Data is generated whenever a medical record is accessed and stored in the journal system. VeriCare temporarily processes this data, comparing it against multiple parameters to assess the likelihood of unauthorized access.

## Challenges

The system evaluates parameters to determine the probability of improper access. However, certain medical workflows—such as doctors urgently responding to a patient while remaining logged into a system—can create seemingly suspicious activity. VeriCare must account for these real-world scenarios to avoid false alarms.
Ethical concerns may arise regarding AI-based monitoring. However, since the system applies uniform criteria without bias, it can be argued that using AI to identify potential violations is no less ethical than allowing unauthorized access to go unchecked.

## What next?

VeriCare has the potential to enhance patient record security. However, implementing the system requires access to sensitive data, raising legal and trust-related challenges. To move forward, the project will need the involvement of more healthcare providers and legal experts to ensure compliance and acceptance within the medical community.

## Acknowledgments

 
* image creator: mcmurryjulie 
  <br>Emr-elektriska-journaler: [https://pixabay.com/sv/vectors/ehr-emr-elektroniska-journaler-1476525/](https://pixabay.com/sv/vectors/ehr-emr-elektroniska-journaler-1476525/) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)

