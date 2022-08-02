PLEASE READ TO UNDERSTAND HOW THE DIRECTORY IS SETUP
# scawatch
Experimental setup, datasets, and code of the SCAWATCH Paper submission to NDSS 23. 



REPO ORGANIZATION:

(1) SENSOR DATA

This contains all SENSOR TRACES from our Experiments, divided into BENIGN and ATTACKS. In the ATTACKS FOLDER, there are are graphical snapshots presented to show when the attacks were injected and the device that experienced the disruption



(2) SCADA EXECUTION DATA

This contains Execution Traces, behavior profiles (i.e., to know which module does what), and code that utilizes the profiles

Thi contains the API traces during our running of the SCADA programs, WinSPS and MySCADA. In there you will find the SCADA profiles or identifiers, which are a mapping to identify which API calls are READ or WRITE. 


(3) TESTBED

This gives information of our FACTORY IO Testbed.


(4) MODEL BUILDING

This contains code, input, and output of our Dependency Modelling tool.

Given an STL, analysis tool builds a device dependency of each process. A sample input STL is given, together with an output dependency file.




