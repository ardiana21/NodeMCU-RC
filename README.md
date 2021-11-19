# NodeMCU-RC
A client-server communication between two NodeMCU

This repository contains code to control an RC car over WiFi using an NodeMCU with NodeMCU

## Requirement

### Hardware Requirement
	- RC Car
		* An Unused/broken RC car
		* A NodeMCU
		* A L298N Motor Driver
		* A Breadboard
		* Some wires
		* Batteries
	
	- Remote Controll
		* A Breadboard
		* A NodeMCU
		* 4 Buttons
		* 4 1k ohm resistors
		* Batteries

### Programming Requirement
	- A Laptop
	- An USB cable
	- IDE (i recommend using Arduino IDE  or VSCode with PaltformIO)
	
## Wiring 

	### Car Wiring
	### Remote Wiring
		
## Security
	For Security reason, 
	make sure you change this 2 lines of codes in both NodeMCU for WiFi Name and Password:
	```
	const char* ssid = "SSID"; //Enter your wifi network SSID
	const char* password = "PASSWORD"; //Enter your wifi network password
	```
