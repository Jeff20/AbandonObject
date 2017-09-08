# AbandonObject
Detection of abandoned object at a station

Developed using OpenCV in Python. The script reads a normal video footage, applies Background Subtraction technique to find contours. Dilation and Erosion techniques are also applied to enhanced the boundaries of the contours. To enhance the accuracy of the detection, the location and movement of each contours across multiple frames are stored in a Python list. And they are analysed to identify suspicious objects which are unattended for a specific period of time.


I am unable to unload the input video file used in the script as it exceed the size limit permitted by Github. Please download the video separately from this link:

i-Lids bag and vehicle detection challenge
(AB: abandoned baggage scenario- AVSS AB Easy)
http://www.eecs.qmul.ac.uk/~andrea/avss2007_d.html

The script are shared as it is. It was written more than 3 years ago with the various packages and versions available at that moment in time. I am not sure if it works with the current versions. Please go through the script and amend the path to the input file, and make any necessary adjustments.

I hope that you will this useful. 
