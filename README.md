# Instrument-Control

1) ### FlashControlPy
This repository contains different codes used in controlling instruments for field assisted sintering, and collecting electrical data from such experiments.

The following codes have been added to the repository:

1. Voltage and Temperature Acquisition code for Field Assisted Sintering - especially Flash Sintering. This can find use in cases where the power source is controled by a different code/software or manually and the voltage and temperature retuned need to be recorded. The information containeed in the summary file can be followed to operate the software correctly.
2. Current Control Approach
3. Voltage Control Approach
4. Flash Sintering Control Full Suite


#### 1. Voltage and Temperature Acquisition Code
- To use this code, the user must enter the correct NIDAQ address for the voltage and temperature, if the user wishes to acquire the voltage using Keihley multimeter also, the user wil have to set the GPIB address to 01 or edit the address in the code. The peak voltage of the power source and the maximum allowed voltage of the NIDAQ must be entered correctly too on the front end to ensure that the correct voltage scale is used. The code automatically saves the data acquired in a selected folder, and plots voltage and temperature against time on two rows.
