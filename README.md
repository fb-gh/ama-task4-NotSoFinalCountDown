# <a name="toc">Table of contents v1.0.1

* [Task 4 - Angular Tutorial](#at)

	* [Introduction](#int)
	* [Project setup](#ps)

# <a name="int">Introduction / Change Log

- Added StackBlitz code for task 4 (v1.0) after tutorial completion
- includes build folder (.\dist)
- updated readme.md as part of task 4 (v1.0.1)

# <a name="ps">Project Setup

 #### Step 1: Install node.js and a npm package manager (included with node.js)
Download and install node.js latest version from https://nodejs.org/
	If in doubt if it is already installed, run the command 
	
  
	node -v

on the command line and if a version is returned, check if it doesn't return any error and is at least greater than v16.16.0 (current at the time of this implementation, lower versions should also work tough). 
The same should be done for the npm packet manager with the below command. The version to look for is 8.11.0
	
  
	npm -v


If so, you may skip this step
	
 #### Step 2: Install angular CLI
 
 On the command line check if the angular CLI is already installed with the following command:
	
  
	ng version

In case of unknown command error, install with command (internet access is assumed):	
  
	npm install -g @angular/cli

 #### Step 3: Choose a or b
 ###### Step 3a: Download code from github
Download the files in a zip and unzip to an apropriately named work folder, clicking on green "Code" button and choosing "Download Zip"

 ###### Step 3b: Clone the cone for a personal git repository
With git installed, on windows explorer an apropriately named work folder, select and clear the address bar and enter the command
	
  
	cmd

and then on the windows CLI window that was created, run 
	
  
	git clone https://github.com/fb-gh/ama-task4-NotSoFinalCountDown

 #### Step 4: Run project

navigate to the created folder 
	
  
	cd ama-task4-NotSoFinalCountDown

and run the commands to configure and run the project (on npm command, if there's errors returned, try adding "--force")
	
  
	npm install
	ng serve

 #### Step 5: Access the generated page

You can now access the generated page on the address http://localhost:4200/
You can use Visual Code to change the project, navigating to the project folder ( < workfolder > \ama-task4-NotSoFinalCountDown) and running the command 
	
  
	code .
