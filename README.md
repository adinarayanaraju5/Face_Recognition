# Project Face Recogniton using LBPH


## Overview
The aim of this project was to create a Face Detection and Face Recognition system. The project is made using python. The face recognition is accomplished using the OpenCV library(computer vision) to detect faces using various algorithms like Haarcascades and LBPH.

## Prerequisites
* [Python](https://www.python.org/downloads/) -With some libaries like opencv,os,nummpy and pillow .


## Setting up the project
> In order to run this face recognition and detection project, you must have python installed on your pc(To install, Click on prerequisites).


```
#Once the project has been setup, navigate to the project directory
cd /Face_Recognition

#To check python version and Start the python
python --version
python

```
## Running the project
```

#Firstly run the face_dataset.py file to get the face of the user and also give a unique id
Python face_dataset.py

#After that run the face_training.py file to train the faces which are present on dataset directory
python face_training.py

#finally run face_recognition.py file to recognize the user with the particular name provided.
python face_recognition.py

```

## Resources
* Balla Adi Narayana Raju - Face recognition - [Balla Adi Narayana Raju](https://github.com/adinarayanaraju5)
*[Face Recognition with openCV](https://docs.opencv.org/2.4/modules/contrib/doc/facerec/facerec_tutorial.html)
