
# Jarvis: Intelligent Attendance System

We worked on the problem statement given by the company "Naturals" at Skit Hackathon 2019.
## Problem Statement: 
 -> To create a intelligent attendance system.
 -> To increase the productivity of service engineers.

# FaceRecognition

This repository is for our team Creation For Innovation submission in SKIT RTU hackathon 2019.


This repository contains code for Attendance Management using Facial recognition.

## To try it:
  1. Clone and download the repo.
  2. Run 'train.py'


Technology used :
  ->openCV (Opensource Computer Vision)
  ->Python
  ->tkinter GUI interface

[![Jarvis: Intelligent Attendance System](https://github.com/abhilashk433/Attendance-system/blob/master/jarvisppt.png)](https://slides.com/abhilashkumar/deck-3#/ "Jarvis Slides")

## How it works :
=======
Technology used:
-openCV (Opensource Computer Vision)
-Python
-tkinter GUI interface

Here we are working on Face recognition based Attendance Management System by using OpenCV(Python). One can mark thier attendance by simply facing the camera. 

How it works:

When we run train.py a window is opened and ask for Enter Id and Enter Name. After enter name and id then we have to click Take Images button. By clicking Take Images camera of running computer is opened and it start taking image sample of person.This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. It takes 60 images as sample and store them in folder TrainingImage.After completion it notify that images saved.
After taking image sample we have to click Train Image button.Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.
Now all initial setups are done. By clicking Track Image button camera of running machine is opened again. If face is recognised by system then Id and Name of person is shown on Image. Press Q(or q) for quit this window.After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time and it is also available in window.

## Thanks:
## Abhishek mohata, Abhilash tiwari(https://github.com/abhilashk433), Dhairya Gulgulia
