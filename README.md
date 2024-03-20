# A simple program to detect drowsiness of a person(aimed to be used by people who are driving)
# Change these threshold values according to your need
These values are to change the detection threshold
EYE_AR_THRESH 
EYE_AR_CONSEC_FRAMES 
YAWN_THRESH 
Python3 drowsiness_yawn.py -- source 0		
--source selects the index of the code
by delfault the program uses source 0 so it is not necessary to specify the source if you have only one webcam.
Use a speech sythesizer like espeak from source forge to get alerts(text to speech).

# resources 
https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html
https://pyimagesearch.com/
https://pyimagesearch.com/2017/10/23/raspberry-pi-facial-landmarks-drowsiness-detection-with-opencv-and-dlib/

# HOPE YOU ENJOY THANK YOU
# by Pranav P

# Note
This code may not work withtout some tinkering ;)