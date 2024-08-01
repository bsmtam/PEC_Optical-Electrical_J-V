Optical-electrical MATLAB model for simulating PEC photoanode, PV-PEC, &amp; PV-E J-V curves developed by Brian Tam <br>
## generatePECPVJV for dual PV cells back-to-back or side-to-side with the PEC 
Run the code by typing in the command window: <br>
generatePECPVJV(PVNumbers,PECBandgap,PVBandgap,front) <br>
For example: <br>
generatePECPVJV(2,2.4,1.1,true)
## generatePECPVtandemJV for tandem PV cells back-to-back or side-to-side with the PEC
Run the code by typing in the command window: <br>
generatePECPVtandemJV(PECBandgap,PVBandgap1, PVBandgap2, front) <br>
For example: <br>
generatePECPVtandemJV(2.4,1.9, 1.1, false)
