Deployed URL:https://mentor-student-db-ofnx.onrender.com/


Key API Endpoints

1.Create Mentor (POST): Establish a new mentor profile.

Endpoint: /mentor/createMentor

2.Create Student (POST): Register a new student.

Endpoint: /student/createStudent

3.Assign Student to Mentor (POST): Link a student to a mentor, fostering a learning relationship.

Endpoint: /assignment/assignStudent/:mentorId/:studentId

4.Assign or Change Mentor for Student (PUT): Assign a new mentor to a student or modify an existing mentor-student relationship.

Endpoint: /assignment/assignOrChangeMentor/:studentId/:newMentorId

5.Get All Students for a Mentor (GET): Retrieve a comprehensive list of all students under the guidance of a specific mentor.

Endpoint: /mentor/getAllStudents/:mentorId

6.Get Previously Assigned Mentor for a Student (GET): Access the historical data of a student's previously assigned mentor.

Endpoint: /student/getPreviousMentor/:studentId

Detail Documentation

For an in-depth understanding of our API and its usage, we recommend referring to our comprehensive Postman Documentation.
https://documenter.getpostman.com/view/29697867/2s9YkgER4L

Credits

This project was successfully completed as part of a task assigned by Guvi. We have diligently adhered to all the requirements provided by Guvi in the completion and submission of this task.
