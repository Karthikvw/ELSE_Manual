# Installation Manual

## Cloning the repository:
Clones and adds repository to the folder
### Syntax
>git clone "***repository link***"  

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
>make install  

**HINT**  
You can control the number of work processes by the below command  
>make -j(n)
(n) - required number of processes

>**NOTES**
>*Make sure you are in ELSE directory  
>*You might need to enter your Github username and password several times
