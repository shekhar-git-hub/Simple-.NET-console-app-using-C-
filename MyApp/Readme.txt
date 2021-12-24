.Net Tutorial - Hello World in 5 minutes


A. Intro

1. Purpose : Install .NET and create a simple application.

2. Scenario: A simple application written in C# that prints Hello, World! to the console.



B. Download and Install

1. To start building .NET apps, download and install the .NET SDK (Software Development Kit).

	Link to download : https://dotnet.microsoft.com/en-us/download


2. Check everything installed correctly. Once you've installed, open a 'new comman prompt
	and run the following command:

	> dotnet

	If the installation, the output is shown similar to the ones in 'Screenshots' folder.
	Check the title name of file.



C. Create your app

1. In your command propmt, run the following command to create your app:

	> dotnet new console -o MyApp

2. Then, navigate to then new directory created by the previous commad:

	>cd MyApp


*Commands meaning:

	a. The 'dotnet new console' command creates a new console app for you.
	
	b. The -o parameter creates a directory named MyApp where your app is stored and 
		populates it with the required files.

	c. The command cd MyApp changes your current directory to the one just created
		for the new app.


* The main file in the MyApp folder is called Program.cs. 
	By default, it already contains the necessary code to write "Hello, World!" to the console.



D. Run your app

1. In your command prompt, run the following command:

	> dotnet run

	Eg: C:\Users\SHEKHAR CHOUDHARY\MyApp>dotnet run


2. Output: Hello, World!

	
	[If the output is shown as desired, we've successfully built the simple .NET app.]



E. Edit your code

1. Open the Program.cs file in MyApp directory, in any text editor such as notepad or VS code, etc.

2. Start editing the code as required.

	For example: 

	// See https://aka.ms/new-console-template for more information
	Console.WriteLine("Hello, World!");
	Console.WriteLine("The current time is " + DateTime.Now);


3. Run same as option D above.

	>dotnet run

4. Output: 
 
	Hello, World!
	The current time is 12/24/2021 12:01:30 PM
	



[Note: Make sure to change to the app directory where c# file is located before running the app]


--> If the output is shown as desired, we've successfully built the simple .NET app. However, we 
	can edit the code as desired to build any advanced .NET application.<--















