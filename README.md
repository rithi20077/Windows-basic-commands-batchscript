# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="520" height="82" alt="Screenshot 2025-11-10 053923" src="https://github.com/user-attachments/assets/993eebf3-a8f3-419a-aeb7-60f112483953" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="600" height="92" alt="Screenshot 2025-11-10 053938" src="https://github.com/user-attachments/assets/b7ddc40b-416b-4b7b-853b-a86f134daee4" />


## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="629" height="367" alt="Screenshot 2025-11-10 054003" src="https://github.com/user-attachments/assets/33fb71e3-649e-44ab-9482-4bd67c192ea1" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="680" height="117" alt="Screenshot 2025-11-10 054017" src="https://github.com/user-attachments/assets/f1b4d27a-8e14-4ef9-9fe9-03ab0cab3e39" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="661" height="130" alt="Screenshot 2025-11-10 054048" src="https://github.com/user-attachments/assets/3cca9028-856a-468d-a08c-8ae317b0f0e1" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="496" height="171" alt="Screenshot 2025-11-10 054137" src="https://github.com/user-attachments/assets/961e2f9b-58bd-4959-bd97-e4c8bc6d23ed" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="619" height="776" alt="Screenshot 2025-11-10 054405" src="https://github.com/user-attachments/assets/ab4a4073-aca8-441a-928f-6344d355eabc" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="576" height="204" alt="Screenshot 2025-11-10 054427" src="https://github.com/user-attachments/assets/68c2f578-1447-4ee6-afaa-0d646b9f540b" />


## COMMAND AND OUTPUT

Compare the file hello.txt and rose.txt

<img width="576" height="204" alt="Screenshot 2025-11-10 054427" src="https://github.com/user-attachments/assets/cab86039-800f-425b-a30b-0ed5ac5391c0" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="474" height="160" alt="Screenshot 2025-11-10 054440" src="https://github.com/user-attachments/assets/511d8b08-412e-4bbf-af0e-8b1e46d0bfbc" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="568" height="212" alt="Screenshot 2025-11-10 054447" src="https://github.com/user-attachments/assets/471fcf8e-7335-4c5c-a5c2-146a93600ba4" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="476" height="230" alt="Screenshot 2025-11-10 054458" src="https://github.com/user-attachments/assets/850cd9c3-1ccc-4d0a-b9c0-1eb6cb5e1c32" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="488" height="184" alt="Screenshot 2025-11-10 054512" src="https://github.com/user-attachments/assets/3461489a-3091-4f07-ac46-c21504d21f95" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="427" height="463" alt="Screenshot 2025-11-10 054517" src="https://github.com/user-attachments/assets/3e233c07-1708-4d90-9ec5-b68d4614435f" />



# RESULT:
The commands/batch files are executed successfully.

