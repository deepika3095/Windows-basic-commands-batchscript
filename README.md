# 212223230038
# DEEPIKA R      
# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/bca2e657-0f8b-4360-bede-4c072774b537)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/2a92519d-e6ec-4217-afb8-16ad394dbe63)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/dfd9173c-41d0-421b-b9f7-ef8409d8a0dc)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/d1480905-b49c-4ad6-bc72-245d3c9df09e)


## COMMAND AND OUTPUT

copy MyFile.txt %userprofile%\Desktop\Backup
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/696c9d98-f83b-46b4-a7bc-21dc59a54c4c)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

## OUTPUT
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/7dc08b01-5b84-4d7b-8b44-c4317c0759b7)

## COMMAND:
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!


## OUTPUT
![image](https://github.com/deepika3095/Windows-basic-commands-batchscript/assets/151625159/7112c251-7bec-4b45-8077-6ec4946ea74c)


# RESULT:
The commands/batch files are executed successfully.

