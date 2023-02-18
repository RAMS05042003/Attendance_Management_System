
# Facial attendance system using python

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) 


### Project explaination
- The Application software is deployed in the admin's system and the admin should start the
system by running it. The homepage is displayed and it consists of five features:
1. Register a new student
2. Take Attendance
3. Manual Attendance
4. View Attendance
5. Exit
- To register a new student the admin should enter the student id and take the image and train
the model. In the phase of training the model take the 50 frames to store them in the local disk
and train the model with the LBPH algorithm. LBPH (Local Binary Pattern Histogram) is
a Face-Recognition algorithm it is used to recognize the face of a person. It is known
for its performance and how it can recognize the face of a person from both the front
face and the side face.
- To take attendance the admin should enter the subject name and the file should be previously
created in the Attendance folder. When the admin clicks on fill attendance the cam detects
whether the person is live or photo. Attendance is recorded if and only if the person blinks his
eyes at least once. The check sheets button is used to check attendance sheets of a particular
subject.
- If any fault occurs the admin has a chance to modify the attendance sheets manually by clicking
on manual attendance
- By clicking view attendance the attendance of a particular subject is displayed along with the
overall attendance percentage of the candidate. The check sheets are also displayed by clicking
on the check sheet button.
- If the admin wants to exit from the system he/she should click on the exit button.

- "We have designed our system in such a way that it will not grant attendance by showing the
photo of the candidates, which remaining applications failed to find the solution.
Our system recognizes the face only if the eye of the candidate blinks more than once."


