Author: Mahbub, Saabah B., Tomczyk, Jakub and Goldys, Ewa M. 
Year: 2020 
Title:GUI_Preprocess version 3.12 
Short Title:GUI_Preprocess version 3.12 
DOI:10.5281/zenodo.4146747 
URL:https://github.com/saabah/GUI_Preprocess.git 


>>AIM:

This GUI actually helps to preprocess the hyperspectral data with respect to supporting reference images. In each experiment, a set of reference images (e.g. calibration, water images, and dark images) is taken using the hyperspectral microscope system to pre-process the sample images. The pre-processing steps include image equalisation, removing undetectable pixels and outliers (spikes), removing background fluorescence and flattening the images. GUI_Preparation preprocess the data by removing the undetectable spikes and dips, removing the background images and flattening the image.

For details, please check the instruction file. 


>>You can cite this software in this format

Mahbub, S.B., J. Tomczyk, and E.M. Goldys, GUI_Preprocess version 3.12 (2020), DOI:10.5281/zenodo.4146747, URL:https://github.com/saabah/GUI_Preprocess.git 


>>> GUI_Preparation Executable

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




