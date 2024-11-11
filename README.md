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

![image](https://github.com/user-attachments/assets/79994867-9fdf-4a04-a243-384e79a8f810)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

![image](https://github.com/user-attachments/assets/a5c55c19-ffce-4eaa-93b5-961a1c3e9d39)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/user-attachments/assets/183b996e-5d79-44cd-b546-5ecadfaff80d)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

![image](https://github.com/user-attachments/assets/f5e2e7c5-1210-4344-b897-82fa7bac4f9e)


## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/fd1e572d-1f4f-4999-a970-ab5e57c832e5)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

open a notepad file named BackupScript.bat and enter the following:
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```
## OUTPUT

![image](https://github.com/user-attachments/assets/6e68a75f-342b-4059-8fe8-0eb1a918892b)

# RESULT:
The commands/batch files are executed successfully.

