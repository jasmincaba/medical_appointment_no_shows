## Introduction
In this project we'll be analysing data from Medical Appointment No Show dataset from
kaggle.com. This dataset consists of 110.527 medical appointments, and 14 variables.

Here is a list of variables:

 - 01 - PatientId : Identification of a patient
 - 02 - AppointmentID : Identification of each appointment
 - 03 - Gender : Male or Female
 - 04 - ScheduledDay : The day of the actuall appointment, when they have to visit the
doctor.
 - 05 - AppointmentDay : The day someone called or registered the appointment, this is
before appointment of course.
 - 06 - Age : How old is the patient.
 - 07 - Neighbourhood : Where the appointment takes place.
 - 08 - Scholarship : True of False
 - 09 - Hipertension : True or False
 - 10 - Diabetes : True or False
 - 11 - Alcoholism : True or False
 - 12 - Handcap : True or False
 - 13 - SMS_received : 1 or more messages sent to the patient.
 - 14 - No-show : True or False( No stands for patient showing up)


In this report we will look how patients who did not appear on scheduled appointment differ
from patients who appeared.Most important variable is No_show and analysis will be focused
on this variable and its relation with day of the week, patient gender and also with data if
patient did or did not recieve sms notification about appointment.
