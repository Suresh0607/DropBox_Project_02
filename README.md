#  Validating DropBox application

   A BDD Automation Test Framework to validate the DropBox Share Folder functionality 

   Built on 
   Selenium WebDriver,NUnit, Specflow, C# 

## CONFIG

1.  `Path` value is where the git clone `https://github.com/Suresh0607/DropBoxProject.git` is done.
     Example cd C:\git Note : This can be changed
	`Path` = "C:\git"
	 Then do Git Clone `https://github.com/Suresh0607/DropBoxProject.git`
						or 
     Copy the Zip File into the `Path` folder and UNZip.
						or 
     Copy the ShareFolder into the `Path` Folder from the DropBox.					
						

2.   Open the Project in The Visual Studio 2017  

3.   Build the Solution. 

4.   Browser is Chrome - Version -  75.0.3770.142 

5.   Provided Option to supply customized Data in the Validate_DropBox.feature 
	 Note: To Upload more Number of files, Add File in the ~\NUnit.DropBox\TestData and simply appened with ":" in the "|UploadFileNames|" section in Validate_DropBox.feature  	
     		
	 
## RUN

1.  Run the Tests from the Test Explorer, if not visible you can open it from the Test>Windows>Test Explorer.                
									Or
2.  Run from the command line using  NUnit.ConsoleRunner

    Open Command Prompt 
	CD `Path`+DropBox_Project_02\NUnit.DropBox\packages\NUnit.ConsoleRunner.3.10.0\tools`
	
	Then Execute 
	
	nunit3-console.exe `Path`+"\DropBox_Project_02\NUnit.DropBox\NUnit.DropBox\bin\Debug\NUnit.DropBox.dll"

3.  Check the Output results in the `Path`+\DropBox_Project_02\NUnit.DropBox\Test_Execution_Reports\index.html 


TODO:

1) Remote Web Driver Implementation 
2) Multi Browser 
3) Distributed Testing.
4) Screen Shots on Failure in Reports
5) Jenkins Intergration
6) Verificaiton check Folder is shared to user or not. 
etc..


