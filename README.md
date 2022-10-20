# Investigate a Dataset

## Dataset Description  

No show appointments is a medical dataset from Brazil collected in 2016 that contains over a hundred thousand samples of whether a patient didn't show up for an appointment or not. It also contains features such as the patient's age, gender, schedule details and health status.  
The following are the columns in the dataset and its characteristics:  

1. **PatientId** - Patient identification  
2. **AppointmentID** - Appointment identification  
3. **Gender** - Male or Female  
4. **ScheduledDay** - Date appointment was set up  
5. **AppointmentDay** - Date appointment was to be made  
6. **Age** - Patient's age  
7. **Neighbourhood** - Where appointment takes place  
8. **Scholarship** - True(0) or False(1)  
9. **Hipertension** - True(0) or False(1)  
10. **Diabetes** - True(0) or False(1)  
11. **Alcoholism** - True(0) or False(1)  
12. **Handcap** - True(0) or False(1)  
13. **SMS_received** - True(0) or False(1)  
14. **No-show** - Yes(meaning the patient didn't show up) or No(meaning the patient showed up)  

## Conclusions  

The appointment show up rate was high at 0.7981 against a no show up rate of 0.2019.  
Out of the people who showed up for the appointment, 0.5179 were female and 0.2801 were male.  
Looking at the proportion of each gender compared in the chart, there were almost consistent show up and no show up across all genders, meaning there is no relationship beteen gender and no show.  
When we break down the attendance to age groups, adults were majority of the attendees while youths were the minority. This proved that Age has some relationship with no show.  
The persons who did not receive SMS had the highest proportion of attendance at 0.5656. This signifies that there was no relationship between SMS received and no show.  

### Limitations  

The AppointmentDay column does not contain the hours and minutes values hence we cannot know the specific time the appointment was made. This limited the analysis of the trend in daily time of appointment show up.  
The dataset did not also feature the distance between the patient's home and the clinic since this could also be a factor for not showing up or showing up. The clinic location was therefore not sufficient without the patient's location.
