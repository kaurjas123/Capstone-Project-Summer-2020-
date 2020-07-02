# Capstone-Project-Summer-2020-
Introduction to proposed project- Home security System

Now-a-days security has become a major concern in the accomodation. This project is designed to overcome the increasing problem of theft in home. The main propose to design this project to overcome the following limitations in the existing system, which are as follows-
●	In the existing system, Raspberry Pi is used that has less processing speed and don’t have built-in hard disk.
●	IR Sensor is being used in existing system, which is suitable for shorter sensing range and even affected by hard objects.
●	This project is only suitable for some limited areas like personal area surveillance such as personal office cabin.
In this project, we are using PIR Sensor, which will detect human motion. All the data in the binary form is collected by this sensor only using RF reciever. The function of RF reciever is to collect data from sensor and send it to LPC2148. LPC 2148 is used as master microcontroller, whereas ESP-32 is used as slave microcontroller. ESP-32 and camera will be interfaced together and whenever any motion is detected, it will collect the image of captured data and send it to cloud storage through wifi module. Notification will be send to registered user through e-mail or phone call. Buzzer is also used to notify. 
