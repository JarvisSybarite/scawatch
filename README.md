PLEASE READ TO UNDERSTAND HOW THE DIRECTORY IS SETUP
# SCAWATCH
Experimental setup, datasets, and code of the SCAWATCH Paper submission to NDSS 23. 



REPO ORGANIZATION:

(1) SENSOR DATA

This contains all SENSOR TRACES from our Experiments, divided into BENIGN and ATTACKS. In the ATTACKS FOLDER, there are are graphical snapshots presented to show when the attacks were injected and the device that experienced the disruption. The SENSOR traces were used to compare against CUSUMs and Invariants, as described in the paper. HMI screenshots of the experiments are provided



(2) SCADA EXECUTION DATA

This contains Execution Traces of SCADA. Execution Behavior profiles (called MODs) are provided which enables the analysis code to know which API modules does what in terms of READs or WRITE-bound control execution. The code that utilizes these profiles are provided to analyze READ and WRITES are also provided. 
  


(3) TESTBED 

This gives information of our leveraged FACTORYIO ICS ENGINE along with the physical processes emulated and how they are emulated. FACTORYIO can be downloaded for free from the vendors (RealPars). 


(4) STL-BASED MODEL BUILDING

This contains code, input, and output of our Dependency Modelling tool based on analyzing the STL (i.e., converted from the FBD).

Given an STL, our tool builds a device dependency of each process. We provide a sample input STL, together with an output dependency file produced by runnin the code on the STL input.





