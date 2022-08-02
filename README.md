PLEASE READ TO UNDERSTAND HOW THE DIRECTORY IS SETUP
# scawatch
Experimental setup, datasets, and code of the SCAWATCH Paper submission to NDSS 23. 



REPO ORGANIZATION:

(1) SENSOR DATA

This contains all SENSOR TRACES from our Experiments, divided into BENIGN and ATTACKS. In the ATTACKS FOLDER, there are are graphical snapshots presented to show when the attacks were injected and the device that experienced the disruption



(2) SCADA EXECUTION DATA

This contains Execution Traces, MOD behavior profiles, and code that utilizes the profiles to analyze the traces. The behavior profiles allow our analysis code to know which module does what in terms of mapping of READs or WRITEs control execution.
  


(3) TESTBED

This gives information of our FACTORY IO Testbed.


(4) STL-BASED MODEL BUILDING

This contains code, input, and output of our Dependency Modelling tool.

Given an STL, analysis tool builds a device dependency of each process. A sample input STL is given, together with an output dependency file.




