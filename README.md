# -Aplications-aplication-with-MYO-armband-
 
This is a project in Python language for digital electronics course 3 University ibagué, our goal was to access the different signals that gives us the bracelet (MYO) to give an application this was achieved move the Jumping Sumo (of the company Parrot) ...
If you use this project and is not a native linux (virtual machine) you must configure the serial port of the machine where you will place the module of the MYO correctly, if you omit this native linux.
Also to help save time and better or work with our project to keep in mind that all compressed codes that are in the link when you run MyoConnect.py must be in the same folder.
Install the following libraries:
MYO:
sudo apt-get install python-pip
sudo pip install PySerial --upgrade
sudo pip install enum34
sudo pip install PyUserInput
sudo apt-get install python-Xlib
sudo apt-get install python-tk

Jumping sumo:
import sumo

Note: if neither of the two devices is not connected generates the connection error.

The main code is MyoConnect.py
You will drive the Jumping sumo with the keyboard computer the file is ff.py and for the proyect is sumo.py in this file you will handle the sumo for the myo
