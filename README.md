# On-Board-Controller
On Board Controller (OBC)
OBC is the main communication hub for all subassemblies in the V2 rover. All communication inside the rover will happen using CAN. OBC will use a Teensy 4.1 as the main microcontroller that will be programmed by the software team using MicroROS. OBC will contain GPS and LoRa modules, will power and monitor 3 fans and status/error LEDs, as well as gather temperature data from the temperature sensor boards (RD1). Additionally, it will also have an IMU chip on-board, while also allowing for the use of an external one. It will use ethernet protocol to communicate any necessary data to the Jetson AGX Orin.  

# Project Description
See Project Spec in files, very detailed and outlines everything needed to be known about the board (Firmware info, design characteristics, features etc.)
