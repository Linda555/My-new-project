
# AI-program that verify intern approved or un approved reading in the patient record.

Final project for the Building AI course

## Summary

The AI-program automatically calculates probability for "not approved" reading and sends a report if a reading in the medical record is listed at "not approved". 
The probability is calculated from caregiver's department in the hospital, work title, journal-aktivity and patient's most recent active visits.


## Background

Every year, care staff read in medical records without having a care-contact with the patient. The integrity of several patients is violated. This is contrary to the Patient Data Act, which points out that you must be involved in the patient's care in order to read the medical record. The care staff leaves a digital footprint in the medical record when it is read, but the problem is that few have time to check the log and this is not routinely managed in all departments. Therefore, it is often up to the patient himself to suspect and investigate who has read in his patient record and if that person is involved in the care. The safety of the journal is not the patient's responsibility by law.. but the responsibility is often placed on the patient.




## How is it used?

The programe is linked to all the healthcare workers that moves in the journal and to activities in the journal. The program examines the employees against several criteria once a month and then sends a report to the system administrator. Suspicious events are then investigated at the department further where the incident took place by an administrator.  In what kind situations is the solution needed. the system will automate and clear data so that the search for violations becomes easier and more manageable.



<img src="ehr-g05113767b_1280.png" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

The program only evaluates the parameters that help the system assess how likely it is that the reading is okay or not, but it can be difficult to determine this as a lot of movement in the medical record can look suspicious when doctors have to rush to a ward urgently and leave the computer and at the same time logged in to a patient without any changes being made so the program must take into account how healthcare professionals work.The program may not be seen as ethically okay, but since programs do not discriminate against events, it can be argued that the use should not be seen as less ethical than letting trampling on journals go unnoticed. 

## What next?

The project can result in a more secure patient record. The difficult thing is that the program must have access to the patient record and its users, which means that there are many laws that need to be examined and care managers may not trust the AI-program at all. I think the project needs more caregivers involved and legal support.  


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
