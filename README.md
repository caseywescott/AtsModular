# AtsModular

A Spectral Modelling Tool for Modular Synthesis 

Coded in SuperCollider

For a description of the calibration process and modular resynthesis, please view the attached pdf version of the information titled "Modular Resynthesis of Spectral Data" paper.

For a verbose description of the process and code with video walkthroughs and audio examples, please view the following video presentation:

https://youtu.be/wrbxDqqFEhg

Here are links to specific walkthroughs within the presentation:

1. Walkthrough of component architecture for calibration and partial resynthesis: 
https://youtu.be/wrbxDqqFEhg?t=163

2. Calibration process walkthrough:
https://youtu.be/wrbxDqqFEhg?t=486

3. Partial resynthesis using two modules:
https://youtu.be/wrbxDqqFEhg?t=815

4. Walkthrough of residual resynthesis by way of a modular bandpass and amplifier pair:
https://youtu.be/wrbxDqqFEhg?t=1100

To run the software, add the supercollider class files AtsCalibration.sc and AtsCV.sc located in the SC_Class_Files folder and recompile the SC class library. 

CODE DEPENDANCY/REQUIREMENT: The calibration code accuracy in AtsCalibration.sc is improved when using Tartini, a pitch tracking plugin. If you can load the enclosed Tartini plugin, uncomment the Tartini reference in AtsCalibration.sc and comment the reference to Pitch.kr.

In the Calibration_Files folder are sample calibration data files that can be used to run the classes. 

All audio examples are enclosed in the Audio_Examples folder

The ATS files used in the video walkthroughs and Audio_Examples are located in the ATS_Files folder. 

For any questions/comments please contact atsmodularproject@gmail.com
