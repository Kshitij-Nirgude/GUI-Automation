============================================================================================================
Created by :					Date : 13 June 2018
1. Kshitij Nirgude
2. Aarohi Mali
3. Mrunali Ruikar
4. Adesh Raut

This program is developed for VASP Solutions LLP, Pune.
============================================================================================================

FAQs :
------------------------------------------------------------------------------------------------------------
What is this program about?
-> This program uses GUI automation to connect to a FTP server (FileZilla) and downloads the files automatically.

------------------------------------------------------------------------------------------------------------
What are the System Requirements?
->
1. Windows
2. Java
3. Python (3.6 or higher)
4. Sikuli (Setup is provided)

------------------------------------------------------------------------------------------------------------
How to run the application?
-> There are some prerequisits to run the application.

1] Directory Initializations :

	1. Open "APPLICATION.bat" file in notepad.
	2. Replace "C:\Users\21ksh\Desktop\GUI_Automation.sikuli\" with the absolute path of the current directory.
	3. Perform step 2 for both the paths in the file.

2] Entering User Credentials : 
	
	1. Open VASP2.py in a text editor. (Preferably Notepad++, to avoid the indentation related problems)
	2. Find "Credentials" 2D array. (on 2nd line)
	3. Here, you have to provide the login credentials for every user.
	4. Edit it as :
		Credentials = [ [ host1, username1, password1 ] , [ host2, username2, password2 ] , [ host3, username3, password3 ] ...etc ] 
	5. Make sure you strictly follow the syntax.
	6. Now, find variable named "cwd". (Line 40)
	7. Replace "C:\Users\21ksh\Desktop\GUI_Automation.sikuli\" with the absolute path of the current directory. 

3] Clearing the Transfer Queues
	
	In FileZilla, make sure that the Transfer Queues are empty for each user.

3] Running the Application

	1. Double click on "APPLICATION.bat".
	2. Sit back and relax. The application will start working, and terminate once the file transfers is complete for every user.
	3. For every user, the program will create a separate folder (named after the username) in current working directory, and store all the downloaded files in it.
	4. The execution log can be seen on the cmd window.
	5. If you want to terminate the program, type ALT + SHIFT + C (or CTRL + C).

------------------------------------------------------------------------------------------------------------
How does it work?
-> 
1. Open "runsikulix.exe". There, you can see the code named GUI_Automation.sikuli.
2. The program is very easy to understand.
3. If there is any problem in step 1, simply open "GUI_Automation.html" in your browser.

------------------------------------------------------------------------------------------------------------
Any problem?
-> Feel free to mail us at nirgudekshitij@gmail.com .
------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------------------------------------------
Thank You!
------------------------------------------------------------------------------------------------------------