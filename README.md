#  Validating DropBox applicaiton

   A BDD Automation Test Framework to validate the DropBox Share Folder functionality

## CONFIG

1.  `Path` value is where the git clone `https://github.com/Suresh0607/DropBoxProject.git` is done.
     Example cd C:\git Note : This can be changed
	`Path` = "C:\git"
	 Then do Git Clone `https://github.com/Suresh0607/DropBoxProject.git`
	
2.   Open the Project in The Visual Studio 2017  

3.   Build the Solution. 

4.   Browser is Chrome - Version - 75.0

	 
## RUN

1.  Run the Tests from the Test Explorer.                 

2.  Run from the command line using  NUnit.ConsoleRunner

    Open Command Prompt 
	CD `Path`+DropBoxProject\NUnit.DropBox\packages\NUnit.ConsoleRunner.3.10.0\tools`
	
	Then Execute 
	
	nunit3-console.exe `Path`+"\DropBoxProject\NUnit.DropBox\NUnit.DropBox\bin\Debug\NUnit.DropBox.dll"

3.  Check the Output results in the `Path`+\DropBoxProject\NUnit.DropBox\Test_Execution_Reports\index.html 


TODO:

1) Remote Web Driver Implementation 
2) Multi Browser 
3) Distributed Testing.
4) Screen Shots on Failure in Reports
5) Jenkins Intergration
etc..


