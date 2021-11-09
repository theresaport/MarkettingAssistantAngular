•	Asp.net Web AP 2,
•	Angular 12
•	VS Code
•	EF Code First

-	EF 6 – code first is used to setup the database and schema
Angular ag grid is used to showing the titles


Ps :  
a)	tried to create in .net core 3.1, but the environment is not ready so used Web Api ver 2.
b)	Angular 12 is used , created the api and consumed inside an ag-grid  via  a service. Other features are to be implemented 

To run : 
Step1 : Backend API ( Code first) Go to ToolsNuget Packagemenager console  ( discard any warnings)  
PM> Enable-migrations //You don't need this as you have already done it
PM> Add-migration Give_it_a_name
PM> Update-database

Step2 : To launch angular 12

	Ng serve –open –port=4200


 
Please refere ReadMe.docx for more info
