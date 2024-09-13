# Support-and-Design_59
Title:- Sign Language Detector

Problem Statement:- 
Sign language recognition systems often struggle with accurately identifying and interpreting hand gestures in real time. This project aims to develop a real-time sign language recognition system using a webcam to detect and classify individual hand gestures. The system will utilize advanced hand-tracking and machine learning techniques to ensure accurate gesture recognition and interpretation. The goal is to provide a reliable tool for effective communication through precise sign language recognition.

Type of sign language used:- ASL (American Sign Language)

Description of our work:-
The main.py is the python file that is used to store the pictures into the directories as a dataset that is used to verify the user input sign. The HandTrackingModule imports HandDetector which extracts the points in the hand of the person to identify the pose and position of the hand. The program once executed stores the pictures of the hand into the directory of which the path is mentioned. The S key in the keyboard is used to store the pictures into the dataset. We need to execute multiple times to store multiple signs into the directories as a dataset.

The verify.py is the python file that is used to match the user input sign with the dataset that we have already stored. It display the name of the sign that is being shown by the user in live process in real time. 

The existing model just detects signs given by one hand without moving. It considers only one hand either left or right. But our project aims to detect two hands of the user and detect the gesture that is being shown by them. And also we are trying to get the simple sentences to translate using our project like "Hello, How are you", "Thank you", "i need some help", etc. This is can help to build a bridge between normal people and physically impaired people. Even though it can't all the language, it tries to do basic sentences. It will be the starting step for the big outcome. 
