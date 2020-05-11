# Emotion-Based-Music-Player-BTP
This project was made by our teams for BTP 7th Semester.

Emotion-Based-music-player 
It's music player with chrome as front-End which has the capablity to detect emotions from the face of user with the help of machine learning algorithm.

This is a project using machine learning for detecting emotions based on the expression of the users. 
The interface is made up of HTML, CSS and JS, and the main code is of Python

Python version: 3.6.5 (Try to download all python modules)
(Important modules: glob, os, numpy, random, argparse, time) 
Eel version: 0.9.10 (download link: https://github.com/ChrisKnott/Eel) 
Opencv version: 3.4.3 (Full opencv module. Fisherface module is must) 
Chrome browser is needed (eel library is specifically designed for chrome)

Download all the files in a folder. Open terminal in the same folder.

Type the command 'python capture.py' in terminal.

A window will open in chrome browser having the interface of the player. 
Select emotion mode from the right bottom corner. 
This will start the webcam. 
Face will be scanned in the ending of the currently playing song. 
You can manually move the song controller near the end to start the function.

When emotion is detected, you can see the name of the emotion in the terminal open.


Note: You can see the images on which assumption of emotion is made in the images folder. 
I advise u to train the model in your pc and then use it(I case you are using any new or updated dataset).




