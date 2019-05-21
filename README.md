# CANBUS_Decoder
This repository contains a CAN-BUS data logger and data decoder-parser script.
Cantools, can, binascii and numpy python-libraries have been used for these scripts.
The can_decoder.py scripts imports the DBC file and the raw data file from the argument directory. A raw data csv file as well as a text file containing physical can messages can be saved by the script.
The DBC file for Kia Soul EV is also included in the /DBC directory [Only for throttle, steering and vehicle speed messages]. 


