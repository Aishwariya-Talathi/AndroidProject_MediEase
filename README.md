# AndroidProject_MediEase - A Multipurpose Medical Application 

We propose an android application which will make life of patients a little easier. 

Modules: 

Patient:
1.	Registration
a.	Enter medical history – past prescriptions, reports images (optional)
b.	Allergies
2.	Locate nearby pharmacies and hospitals
3.	Reminder for taking medicines on time pertaining to prescription
Doctor:
1.	Registration
a.	Specialty, address
b.	Qualifications
2.	Receive requests from patients and connect to patients
3.	Reply with proper prescriptions to patients based on their medical history and current health situation



Implementation:
1) Patients log into the system (Google/Facebook/Email login)
2) Patient prescription and report data taken through image recognition by capturing a photo. 
   Image Processing using Optical Character Recognition (OCR).
3) Patients can Locate nearby hospitals and pharmacies done by using Google Places API
   Suggest nearby hospitals using Natural Language Processing.
   Sentiment Analysis is used for Reviews Classification and Best Hospital suggestion.
4) Cloud Messaging for connecting patient and doctor, also used for instant messaging
5) Reminding the user with notifications for taking medicines using AlarmManager for keeping track of time.
6) SQLite and Shared Preferences are also implemented




