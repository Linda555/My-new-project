
# AI-program that verify intern approved or un approved reading in the patient record.

Final project for the Building AI course

## Summary

The AI-program automatically calculates probability for "not approved" reading and sends a report if a reading in the medical record is listed at "not approved". 
The probability is calculated from caregiver's department in the hospital, work title, journal-aktivity and patient's most recent active visits.


## Background

Every year, care staff read in medical records without having a care-contact with the patient. The integrity of several patients is violated. This is contrary to the Patient Data Act, which points out that you must be involved in the patient's care in order to read the medical record. The care staff leaves a digital footprint in the medical record when it is read, but the problem is that few have time to check the log and this is not routinely managed in all departments. Therefore, it is often up to the patient himself to suspect and investigate who has read in his patient record and if that person is involved in the care. The safety of the journal is not the patient's responsibility by law.. but the responsibility is often placed on the patient.




## How is it used?

The program is linked to all the healthcare workers that moves in the journal and to activities in the journal. The program examines the employees against several criteria once a month and then sends a report to the system administrator. Suspicious events are then investigated at the department further where the incident took place by an administrator.  In what kind situations is the solution needed. the system will automate and clear data so that the search for violations becomes easier and more manageable.



<img src="ehr-g05113767b_1280.png" width="300">


## Data sources and AI methods
Data is created when a journal is visited and the data is stored in the journalsystem. The AI-program borrows the data temporarily and matches it against several parameters to determine different probabilities.

## Challenges

The program only evaluates the parameters that help the system assess how likely it is that the reading is okay or not, but it can be difficult to determine this as a lot of movement in the medical record can look suspicious when doctors have to rush to a ward urgently and leave the computer and at the same time logged in to a patient without any changes being made so the program must take into account how healthcare professionals work.The program may not be seen as ethically okay, but since programs do not discriminate against events, it can be argued that the use should not be seen as less ethical than letting trampling on journals go unnoticed. 

## What next?

The project can result in a more secure patient record. The difficult thing is that the program must have access to the patient record and its users, which means that there are many laws that need to be examined and care managers may not trust the AI-program at all. I think the project needs more caregivers involved and legal support.  


## Acknowledgments

 
* image creator: mcmurryjulie 
  <br>Emr-elektriska-journaler: [https://pixabay.com/sv/vectors/ehr-emr-elektroniska-journaler-1476525/](https://pixabay.com/sv/vectors/ehr-emr-elektroniska-journaler-1476525/) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)

