# EXPERIMENT--01-ALP-FOR-8086
Name : SANGEETHA.K
Roll no : 212221230085
Date of experiment : 09/09/2022





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP
```
name "ADDITION"
org 100h
MOV AH,05H;
MOV BH,02H;
ADD AH,BH;
MOV CH,AH;
MOV AH,00H;
HLT;
```

## Output  
 ![189373602-d4e28797-4b18-4b77-bac9-0a7c0ff7e7e7](https://user-images.githubusercontent.com/93992063/189384152-b0414392-714a-4ea7-8418-3565f10e280b.png)

## Subtraction   of 8 bit numbers  ALP 
```
name "SUBTRACTION"
org 100h
MOV AH,09H;
MOV BH,03H;
SUB AH,BH;
MOV CH,AH;
MOV AH,00H;
HLT;
```
## Output  
![189373659-dcf9df19-0f35-4847-a08e-bc4b46b3b132](https://user-images.githubusercontent.com/93992063/189384353-a531122a-2c36-4ba3-8e45-c4a5551a21d9.png)

## Multiplication alp 
```
name "MULTIPLICATION"
org 700h
MOV AL,15H;
MOV BL,03H;
MUL BL;
MOV CL,AL;
MOV AL,00H;
HLT;
```
## Output  
![189373689-403eb021-92a1-4213-9d30-48905a6df3b7](https://user-images.githubusercontent.com/93992063/189383856-d486bc0d-f7c2-4b33-9dc5-2ec1613ddfc8.png)


## Division alp 
```
name "DIVISION"
org 700h
MOV AL,40H;
MOV BL,02H;
DIV BL;
MOV CL,AL;
MOV AL,00H;
HLT;
```
## Output  
![189373709-03700116-6e6a-4b3e-b332-a52bb63de98a](https://user-images.githubusercontent.com/93992063/189383941-f7d97ae3-1269-48da-a624-ce0f56346ab9.png)


## Result :
 Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.








