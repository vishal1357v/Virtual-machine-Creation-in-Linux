 ## NAME: VISHAL P
 ## REGISTER NUMBER: 24901233
 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
  To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

1. Displaying the current directory, files, and system date.
2. Reading and displaying file contents.
3. Performing basic arithmetic operations.

## REQUIREMENT
1. Oracle VM VirtualBox MAnager
2. Kali Linux
3. Mousepad (Text Editor)
4. Terminal

## ALGORITHM
 ### Steps 1:
Open the terminal in Kali Linux.
    
 ### Steps 2:
Use basic Linux commands to navigate and manage files.

    
 ### Steps 3:
Create a Bash script using Mousepad.

 ### Steps 4:
Write a script that performs arithmetic operations and reads a file.
 
 ### Steps 5:
Make the script executable.

 ### Step 6:
Run the script and observe the output.
     
## COMMANDS
##    Execute Basic Linux Commands in the Terminal
## Check the Current Working Directory
```pwd```
## Create a New Directory
```mkdir my_experiment```
## Navigate into the Directory
```cd my_experiment```
## List the Files in the Directory
```ls```
## Write Some Text into the File
```echo "Hello, this is a test file." > myfile.txt```
## Read the File Contents
```cat myfile.txt```
## Get the Current Date and Time
```date```
## Writing a Bash Script in Mousepad
## Open Mousepad
```mousepad myscript.sh &
## Write the Bash Script
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"


## Make the Script Executable
chmod +x myscript.sh
## Run the Script
./myscript.sh
```


## OUTPUT


![419298443-1ff74ab9-312a-489a-a4d0-23ba98156543](https://github.com/user-attachments/assets/cd1afe9b-9efd-4afa-934a-c0e72aa0b446)




## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
 

  


