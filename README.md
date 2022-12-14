# No-show-appointment
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
#### ABOUT PROJECT
Exploratory data analysis on "No show Appointment" Dataset

Project seeks to understand the factors important to predict if a patient will show up for their scheduled apppointment or not
#### ABOUT DATASET

 The dataset collects information from over 100,000 medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
 14 variables (Characteristics) associated with each observation are listed as follows:
 
- Patiend ID- Patients's unique identification number
- Appointment ID- Each appointment generates a unique ID
- Gender- Male or Female
- ScheduledDay- The day someone called to register the appointment(This is before the appointment)
- AppointmentDay- The day of the actual appointment where the patient is to meet with the doctor
- Age- How old the patient is
- Neighborhood- The location of the hospital
- Scholarship- Indicates whether or not the patient is enrolled in Brasilian welfare program [Bolsa Familia](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia)
- Hypertension- Whether or not the patient is hypertensive
- Diabetes- Whether or not the patient is diabetic
- Alcoholism- If the patient is an alcoholic
- Handicap- Whether or not the patient has any form of disability
- Sms Received- 1 or more messages sent to the patient probably as a reminder
- No show- Whether or not the patient showed up for their appointment as scheduled.

#### Questions investigated in my analysis
> 1. Which Gender is most likely going to show up for their appointment and which is not.
> 2. Is age a determining factor to showing up for appointments as planned
> 3. Is the gap in time between scheduled day/time and appointment day/time a determining factor?
> 4. Are scholarship beneficiaries likely to default compared to Non beneficiaries
> 5. Are patients who receive reminders showing up than patients who do not?

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Key Insights 
> 1.  We found that there is no difference in the behavior of both genders, as both genders show up for appointments in equal proportions (80%)
> 2. We found that there was no significant difference in how different age groups showed up for appointments but the **Aged(65+)** slightly performed better (85%) compared to other age groups, this is no suprise as aged patients mostly require medical attention and will likely take their health issues more seriously. 
> 3. It was evident wait time had slight effect on absence with just 66% of patient's with wait time greater than 120 days showing up to their appointment as scheduled while those with wait time 0-60days performed better with 80% shows and 61-120days with 72% shows respectively.
> 4.  Though the difference was not significant, non-scholarship beneficiaries who paid for their health needs tend to show up better than those who benefited from the Bolsa familia scheme. 
> 5. Sms reminders did not seem to matter in determining how patients show up to their appointments, infact patient's who did not receive sms (83%) showed up to their appointment better than those who did receive sms (72%)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### Tools used
- Python libraries 
> Pandas  
> Matplotlib  
> Seaborn  
> Numpy


_N.B. This dataset was openly sourced from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)_
