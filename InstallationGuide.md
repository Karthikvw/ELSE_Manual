# Installation Guide

## Cloning the repository:  
Clones and adds repository to the folder  
### Syntax  
>git clone "***repository link***"  

## Checking the status:  
Checks the status of the cloned repository  
### Syntax  
>git status  

## Recent repository status:  
Provides the recent status of the loaded repository  
### Syntax  
>git fetch  

## Updating ELSE:  
Updates ELSE to the new reviewed version  
### Syntax  
>git pull  

## Creating and changing to build directory  
Making a new directory build where all the executable files are generated and stored later  
### Syntax  
>mkdir build  
>cd build  

## Generating the executables  
Generates the executables which enables the Python code to run  
### Syntax  
>cmake ..  
>make  

## Fixing the Python path  
The Python path can be fixed permanently by the following steps  
*Copy the Python path name from cmake output  
*Open .bashrc file  
*Paste it or replace the existing with the copied path  

>**NOTES**  
>*Step 2 is optional  
>*Updating a new version requires only steps 3,4 and 5  
>*You might need to enter your Github username and password several times  
  
