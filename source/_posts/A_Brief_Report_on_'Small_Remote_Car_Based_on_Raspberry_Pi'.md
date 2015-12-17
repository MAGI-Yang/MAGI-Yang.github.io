## A Brief Report on 'Small Remote Car Based on Raspberry Pi'


## 

*This short report is a brief introduction to the project that I took part in during the past few weeks*

#### Aim of the Project 

The main aim of the project is to produce a small smart car which can be controlled by a client on pc or smart phone via network. By controlling a video camera and some servo motors, the car can run and transfer the real-time video to the client and could be used for unmanned monitoring or long-distance monitoring.

The hardware is based on the Raspberry Pi(RPi) -- A credit card-sized single-board computer developed in the UK by the Raspberry Pi Foundation. The OS of RPi is Debian GNU/Linux, and all the controller programs were written in C/C++. The whole project was mainly divided into three modules -- *communication module*, *monitor module* and *motor module*.

#### What I Have Done in the Project

###### Side of Communication Module

I worked for the communication module in the project, and my work was to build the connection between the car, host server and the control client. The codes of the server and clients were written in C++. After both client and car were connected to eh server, once the client send a command to the host server, the server will resent the commands to the car side. 

###### Side of Monitor Module

In fact, at free time, I also try something fun using this system. By using the camera and OpenCV Library, I built a small face detection system. Anybody who walks past from the camera may be taken a picture of his face, and this picture will then be sent to a specific e-mail address with a text message 'I find you!' in the mail.

#### Where Will the Project Go

At present, this car can *run* and *see* while in the original conceive of the project, I hope the could get the ability to 'feel' this  world. 'Feel' means it may recognize where it is or what is around itself or who it is facing to(not only detection,but also recognition.) 

It seems that lots of work remains to be done.

#### Ending

As what I said at the beginning,this short report is just a brief introduction to the project that I took in the past few days. Some detail information might not be clearly stated. I'm very willing to start discussion on a proposal with you.

*Thanks for your reading.*

-----
