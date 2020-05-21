# DatingApp
## Shortcut commands which can be used in this application. Angular, .NET CORE

** We can achieve all the activities of jquery by using pure Angular.

** <dotnet new Project_Name> ---- create a new .net core project with name <Project_Name>
** <Code .> ---- open a .Net core project.
** <dotnet run> ---- run .NET core project
** <dotnet watch run> ---- run .NET core project. If you save the changes during running of the project, it will rerun. automatically.
** <dotnet ef migrations add AddedUserEntity> --- add entity framework class to project with name "AddedUserEntity"
** <dotnet ef database update> --- update database schema from the entity framework
** <dotnet user-secrets> --- see secret storage options
** <dotnet user-secrets init> --- initialize secret storage in the development machine.
** <dotnet user-secrets set "Appsettings:Token" "super secret key"> --- "super secret key" is stored at the secret storage in the machine which can be used in json Appsettings:Token in file appsettings.json
After running this command, we can remove the json ["AppSettings":{"Token":"super secret key"}] from the appsettings.json file and let this file move into source control.
(This Json content should be placed in the appsettings.json at the top when not using secret key storage.)

**<dotnet user-secrets list> --- show the list of secret storage in local machine.
 

** <ng new Project_Name> ---- create a new angular project with name <Project_Name>
** <ng serve> ---- run an angular project.

Steps to use github:
Install git bash into your local system.
Then set user name and email id in git bash.
Restart application.
** <git init> initialize a git repository for the complete project. 
** <git remote add origin https://github.com/PranayShandil/DatingApp.git> push the whole project to new repository
** <git push -u origin master> push files to git from terminal window.(this will sync local checkin to github repository)