# E*as*YE TRACKING with OPENCV

![](https://github.com/chiaracoletti/EasYE-tracking/blob/master/Readmefiles/EasYE_TRACKING_logob.png)

We are developing an easy and accessible eye tracking software that identifies faces, eyes and iris in a video, and provides an immediate visual representation of the iris movement throgh a scatterplot.
It requires only a common computer and the open source **OPENCV** library to work (NO expensive hardware required!!!).
We chose opencv because it is open source, easy to use, and it provides some great code for object detection in images and videos, which perfectly fitted our needs. 
The code is written in Python.

##Contents
* ***eyetracking_scatter.ipynb*** is the complete program that identifies faces, eyes, iris and pupils and allows to have a simple yet immediate graphic representation of the eyes movement through a scatterplot.
* ***eyetracking_direction_leds.ipynb*** is a version of the same program implemented with a more precise approach to the pupil tracking, based on colour gradient. It also shows the gaze direction turning on and off four leds.
* ***Latex*** is a folder that contains a Tex file with more specific documentation of our work. Sorry, italian! :)
##Getting started
* Make sure you already have opencv on your computer, the cascade classifiers we used should already be included. 
* Move the cascade classifiers' files in your working directory.
* Download the code and enjoy! (we used jupyter)

##Creators:
We are two students of Biomedical Engineering @Politecnico di Milano, this project is the final result of our Computer Science course. 
We are also participating in the Xilinx Pynq Hackathon, in july 2016.
Please, feel free to contact us:

giada.colella@mail.polimi.it:

![](https://github.com/chiaracoletti/EasYE-tracking/blob/master/Readmefiles/foto1_readme.png)

chiara.coletti@mail.polimi.it:

![](https://github.com/chiaracoletti/EasYE-tracking/blob/master/Readmefiles/foto2_readme.png)

Thanks for your attention :)
