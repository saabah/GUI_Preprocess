Author: Mahbub, Saabah B., Tomczyk, Jakub and Goldys, Ewa M. 
Year: 2020 
Title: GUI_Visual version 1.1 
Short Title: GUI_Visual version 1.1 
DOI: 10.5281/zenodo.4146738 


>>AIM:

All the hyperspectral images were stored in a special Matlab file data file (*.mat). As such, a custom made Graphical User Interface (GUI Visualization ver 1.0) has been developed to inspect the taken images and to extract other information. For details, please check the instruction file. 


>>You can cite this software in this format

Mahbub, S.B., J. Tomczyk, and E.M. Goldys, GUI_Visual version 1.1. (2020), DOI: 10.5281/zenodo.4146738, URL: https://github.com/saabah/GUI_Visual.git


GUI_Preparation Executable

1. Prerequisites for Deployment 

Verify that version 9.7 (R2019b) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2019b 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-GUI_Preparation.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.




