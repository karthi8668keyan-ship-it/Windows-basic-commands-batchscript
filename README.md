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

## COMMAND AND OUTPUT

<img width="404" height="105" alt="image" src="https://github.com/user-attachments/assets/fa240f72-4546-478c-bd29-959780988b34" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="416" height="106" alt="image" src="https://github.com/user-attachments/assets/28696fee-7d60-45e2-a84d-f5b317ee106d" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="535" height="116" alt="image" src="https://github.com/user-attachments/assets/310ee177-8de0-45bd-a0c2-79cb5b6a8920" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="571" height="109" alt="image" src="https://github.com/user-attachments/assets/61c884bd-64f8-4018-bd02-14e2fea30695" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="507" height="79" alt="image" src="https://github.com/user-attachments/assets/9fa855d5-ca10-4235-b96b-4ef8ddc00c0b" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="422" height="110" alt="image" src="https://github.com/user-attachments/assets/2ea6bed0-73e3-4414-98c4-55b093f506c4" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="456" height="175" alt="image" src="https://github.com/user-attachments/assets/096ecad5-2a52-4c5a-a82a-17213c0e91be" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="307" height="489" alt="image" src="https://github.com/user-attachments/assets/893697d2-fb32-4302-a697-5db2072f2b65" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="476" height="187" alt="image" src="https://github.com/user-attachments/assets/6b228576-17ca-4580-830f-57a4e8b53925" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="542" height="85" alt="image" src="https://github.com/user-attachments/assets/2c359beb-0a40-4c29-bc32-055a1d3b9d86" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="576" height="346" alt="image" src="https://github.com/user-attachments/assets/a072bcfa-35f1-46c2-8e84-7b9d44d2ffcb" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="532" height="184" alt="image" src="https://github.com/user-attachments/assets/ebfc11c9-01f1-4ae3-965c-6e5e042cebe7" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="564" height="106" alt="image" src="https://github.com/user-attachments/assets/5d4bb99b-8eac-4a98-ad59-ce6c88118583" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="561" height="345" alt="image" src="https://github.com/user-attachments/assets/f7b539c6-b205-4376-b6ab-502736c175e9" />


# RESULT:
The commands/batch files are executed successfully.

