# ExcelReader

## **About:**
An application that can read Excel files and print on Console.

## **Features:**
- Login using a registered username and password. 
- User will get an option to upload/download a file.
- If user selects upload then it redirects to Upload page where the authenticated user can select a text file from any directory. This file will first get encrypted using Reverse Caesar Cipher algorithm and then it is uploaded to Dropbox.
- The file can be viewed by the server administrator but it cannot be read.
- If the user selects Download option the user is redirected to a download page. He has to enter the same file name “Encrypted” appended at the beginning of the filename.
- Once the file is downloaded it gets stored in home/lenovo/dropbox folder

## **To Run This Project:**
## **Requirements:**
- jdk (>=1.7) 
- Eclipse/Netbeans/any other IDE 

## **Steps:**
1. Open Eclipse/Netbeans/any other IDE, open this project then build & run.

2. Replace file "exceldatabase.xls" with your excel file and change file name in ExcelToConsole.java class.

**This project was developed in Eclipse IDE.**
