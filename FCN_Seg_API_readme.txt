FCN_Seg_API Executable
Auto ML for Image Segmentation

1. Prerequisites for Deployment 

Verify that version 9.11 (R2021b) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2021b 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-FCN_Seg_API.exe
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

4. How to run CLI

funciton CLI: FCN_Seg_API.exe  imgDir, labelDir, inceptionresnetv2, mobilenetv2, resnet50, resnet18, xception, adam, sgdm, rmsprop, Batch, Eopach, DisplayProgress, UsingGPU
example  CLI: FCN_Seg_API.exe ('img\','label\', '0', '1', '0', '0', '0', '1', '1', '0', '5', '5', '1', '1')


https://drive.google.com/drive/folders/1Eiuom5CHP-DnSojIsTEr0TsfTSUK6vU7?usp=sharing