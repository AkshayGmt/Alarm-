Develop an Alarm Clock:

About the python Projct:
The objective of our project is to implement an alarm clock using Python. Python consists of some very innovative libraries such as datetime and tkinter which help us to build the project using the current date and time as well as to provide a user interface to set the alarm according to the requirement in 24-hour format.

Prerequisites
This project requires good knowledge of Python and GUI (Graphic User Interface). Python when combined with Tkinter provides a fast and easy way to create GUI applications. Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.

Project file structure:

Importing all the libraries and modules required
Putting forward a while loop which takes the argument of the time, the user wants to set the alarm on and automatically breaks when the time is up, with sound
Create a display window for user input.
1.First, we import all the necessary libraries and modules:
 Tkinter module belongs to a standard library of GUI in Python. It helps us to create a dialog box with any information that we want to provide or get from the users.
Datetime and time modules in python help us to work with the dates and time of the current day when the user is operating python and to manipulate it too.
Winsound module provides access to the basic sound playing machinery provided by Windows platforms. This is useful to generate the sound immediately when a function is called.

2. Create a while loop:
Define a function named as alarm() which takes the argument of (set_alarm_timer).It contains a while loop with a Boolean function True which makes the program automatic to work.
time.sleep(1) halts the execution of the further commands given until we get the time value from the user later in the code and returns the background thread of the clock time going on at a regular interval.
Get the current time using current_time which takes the argument of datetime.datetime.now().
now is used to print the time and date is used to print the current date by string conversion using strftime().
Define another function here named actual_time() which takes in the user value for setting the alarm in the string format. The same argument of (set_alarm_timer) as alarm before to execute the while loop which we further use while making GUI.
If loop suggests that if the user input time set_alarm_timer matches with the while loop ongoing time now, the message is printed as” Time to Wake up”.
winsound.SND_ASYNC plays the system generated sound as soon the condition satisfies, acting as a reminder for the alarm clock.
