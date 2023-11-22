# face-recognition-based-attendance-system


This repository contains code for face recognition based attendance system using openCV and python with a tkinter gui interface. 

Run: train.py

Technology used :
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface



When we run train.py, a window is pops open and asks for Id and Name of the person. 
After enter the name and id, we have to click Take Images button. By clicking on it, the camera of running computer is opened and it starts taking image samples of the person. This Id and Name is stored in a folder named 'StudentDetails' and file name is 'StudentDetails.csv'. It takes 60 images as sample and store them in folder named 'TrainingImage'. After completion it notifies that iamges have been saved.

After taking image samples, we have to click Train Image button. Now it take few seconds to train with the images that were taken earlier and creates a 'trainner.yml' file.
Now all initial setups are done. By clicking Track Image button camera of running machine is opened again. If face is recognised by system, then the Id and Name of person is shown on screen. 
Press Q(or q) for quit this window. After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time.
