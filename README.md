# FortressApp-Readme

## Background

  Fortress Arts Academy  is a community organision in Sout hWest Philly serving the community through the use of the arts and economic opportunity and education.
  
 <b><ins>Fortress Arts Summer Program</b></ins>
 
  Fortress Arts Summer Program is a 8 week long summer program that teaches black youth in the Kingsessing neighborhood of SW Philadelphia skills inlcluding minfulness/meditation, political education, urban farming, entreprenuership, and inner/interpersonal skills. Staff is paid a living wage and students are given breakfast and snacks and paid a base pay of $8 p/h with room to grow. It is a 9am - 5pm program, with program wide trips and relationships with other organisations in Philadelphia including studio 34, and John Heinz conservation Park. 
  
  <b><ins>Program Assesment Needs</b></ins>
  
   It is important for programs like the FA summer program to have asssesments to track the learning and progress of students for pedagogical, and funding reasons. With the immense volume that these students are learning each summer and the qualitative nature of these skills, data can be difficult to quantify. This is where the FortressApp comes in.
   
## Fortress App 

<b><ins>Function</b></ins>

 Fortress App will allow staff to assess student progress every day for each subject they are teaching. It will aso serve as a time sheet where staff can track their hours. Students will also be able to track their time in the time sheet portion and will also be able to track their understanding of all sujects they are learning for the day and their level of interest. 
 
<b><ins>Implementation</b></ins>

 FortressApp will run on ASP.NET CORE in C# leveraging the RESTFul API interface, JavaScript, and a database management system like SQL server. It will use design patterns such as DAO, MVC, and dependency injection.
 
 <b><ins>Time Sheet</b></ins>

 The timesheet will have these main feilds:
 
    start time
    end time
    date
    class
    student/staff ID
    created by, created on(day)- baackend audit (not visable to user)
    
 <b><ins>Assessment</b></ins>

 There will be two sections of the assessment. One for staff, and one for students. Visability of either section will be dependent on the user ID. The staff section of the assessment will include these main feilds:
   
    1.Did students participate in the ecxersise given
     (y/n)
      
    2.If yes, did the student show content mastery
     (y/n)

    3.Is the student able to grasp the concept on a scale from 1-5
     
      1-could  not grasp concept
      2-paritally grasps concept
      3- could grasp the concept but not able to apply it
      4- can grasp concept, partially able to apply it
      5-can grasp concept and apply it fluently 
      
  The student section will have these main fields:
 
    1. Do you feel like you understand the topic of today's lesson? Please rate your level if understanding on a scale from 1-5
 
      1-I could not understand this at all, it might as well have been taught in a different language
      2-I barely understand the lesson 
      3-I somewhat understand the lesson and can explain the topic on a small scale
      4-I understand the lesson mostly
      5-I got this! I can understand AND help my class mates understand it as well!
      
    2. How much did you enjoy this lesson?
      
      1-Borrrriinnng, this put me to sleep
      2-Ehh, it was ok but could be way more interesting
      3-It was alright but could uses some memes
      4-It was interesting! Just needed a little spice
      5-I loved it!
       

     
    
 
 
     
        
