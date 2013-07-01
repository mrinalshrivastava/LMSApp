LMSApp
======

Mayank's project

Login User will navigate to this screen after
Yes Web service will be used to login into
the application.
splash screen is successfully loaded. This
screen will be used to login into the
system. There will be two type of login in
application student login and teacher login.
Screens will be shown as per the type of
login. Successful login will send a unique
ID of the user to service to identify the type
of user.
Yes Web service will be used to login into
the application.

Start the class Tab User will navigate to this screen after
selecting "Start the Class" on the home
screen. This creen will contain a button at
the centre of the screen which will say
"Start lecture". Tapping on Start lecture
button will show a list of the  class
associated to the teacher. After selecting
the class it will send a request to all the
student of selected class to join the table
of teacher. This will be done by sending a
push notification to all the student  of the
class. After sending the successful request
to student button will convert to Stop
Lecture. After tapping the Stop button
again a push will be sent to all the
students to disconnect the lecture.
Yes Start a class web service will be used to
send a notification to all the students of
the class and stop a class web service
will be used to stop the class.

Online Student Tab User will navigate to this screen after
selecting "Online Student" on the home
screen. This screen will show the list of all
the online students who are connected the
tablet. If student is present in the class and
has accepted to connect to the teacher
then a green circle will be shown which will
identify that he is present in class and red
circle will show that he is not accepted to
connect and not present in class.
Yes Web service will be used to list all the
student who have accepted the to
attend the class and are present in
class.



Test List Tab User will navigate to this screen after
Yes Web service will be used to get list of
all the tests created for the subject.
selecting "Test List" tab on the home
screen. This screen will show list of all the
tests on past. Tapping on the list will
navigate to a report screen.



Report Screen User will navigate to this screen after
Yes Web service to generate result of all the
sutdent for a specific subject.
selecting the test from "Test List" tab. This
screen will show list of all the student and
the report of the test selected. User can
see the report of all the students in this
screen. This screen will also contain a print
button. Tapping on the print button report
will be printed on the printer connected  via
wifi.

Add a test User will navigate to this screen by
Yes Web service to create a test.
selecting the Grid Condition Tab on the
Home Screen. This screen will show the
current condition of the Grid. This screen
will refresh in every 5 min interval

Join Lecture Tab User will navigate to this screen after
Yes Web service will be used to join the
lecture.
selecting the "Join Lecture" tab from Home
Screen. This screen will show a button at
the centre of the screen. This button will
become active when the a lecture is
started (i.e. A teacher has started a
lecture). When user will tap on the button
he will get connected to the tablet of
teacher and will be able to join the lecture
and give paper.



Test List Tab User will navigate to this screen after
Yes Web service will be used to list all the
tests assigned to this user.
selecting "Test List" tab from Home Screen.
This screen will show list of all the test
assigned to the user. User can tap on the
test and will navigate  to a test screen.
This screen will contain all the questions of
the paper. User can give the relevant
answer and tap on submit button. This
submit button will call a web service and
result of the test will be added to the Test
Report tab.


Test Report Tab User will navigate to this screen after
Yes Web service will be used to generate
report of all the test given by the user.
selecting "Test Report" tab from Home
Screen. This screen will show list of all the
subjects that user is assigned to. Tapping
on the subject user will navigate to a
screen showing list of all the tests user has
given in past for the selected subject.


Push Notification
Implementation
Handling the notification service and
sending the device token to the server.
Yes Web service to send the device token to
server.
