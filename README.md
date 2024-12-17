# DatingApp

## Shortcut commands which can be used in this application. Angular, .NET CORE

\*\* We can achieve all the activities of jquery by using pure Angular.<br />
\*\* <dotnet new webapi -n Project_Name><br />
\*\* create a new .net core project with name <Project_Name><br />
\*\* <Code .> ---- open a .Net core project.<br />
\*\* < dotnet run> ---- run .NET core project.<br />
\*\* < dotnet watch run> ---- run .NET core project. If you save the changes during running of the project, it will rerun. automatically.<br />
\*\* < dotnet ef migrations add AddedUserEntity> --- update database entity and add entity framework class to project with name "AddedUserEntity"<br />
\*\* < dotnet ef migrations remove> --- remove the current ef migrations if its not updated in database.<br />
\*\* < dotnet ef database update> --- update database schema from the entity framework<br />
\*\* < dotnet ef database drop> --- drop the database<br />
\*\* < dotnet user-secrets> --- see secret storage options<br />
\*\* < dotnet user-secrets init> --- initialize secret storage in the development machine.<br />
\*\* < dotnet user-secrets set "Appsettings:Token" "super secret key"> --- "super secret key" is stored at the secret storage in the machine which can be used in json Appsettings:Token in file appsettings.json<br />

#### After running this command, we can remove the json ["AppSettings":{"Token":"super secret key"}] from the appsettings.json file and let this file move into source control. (This Json content should be placed in the appsettings.json at the top when not using secret key storage.)<br />

\*\*<dotnet user-secrets list> --- show the list of secret storage in local machine.<br />

** < ng new Project_Name> ---- create a new angular project with name <Project_Name><br />
** < ng serve> ---- run an angular project.<br />
** < ng add ngx-bootstrap> --- add bootstrap to angular project<br />
** < npm install font-awesome> ---
** Alt + Shift + F --- Format .ts files<br />
** < npm install JS_NAME> --- install component with the name JS_NAME<br />
** < npm install alertifyjs> --- installs alertify.js component in the angular application which is used to
show formatted alert popups.<br />
** < npm install @auth0/angular-jwt> --- installs tool to check token at the server side without sending the
request to client side.<br />
** prettier tools doesn't works some times even after installing. so use the below link to edit settings.json to make it work: https://www.robinwieruch.de/how-to-use-prettier-vscode<br />
** < npm install ngx-bootstrap --save><br />
** < npm install bootswatch> --- provides theme to the application https://bootswatch.com/<br />
** < Material icon theme> --- this extension provides icons for files in .NET core. To select the theme go to
File > Preferences > File icon theme > now choose your icon theme.<br />
\*\* <npm install @kolkov/ngx-gallery --save> --- Gets the gallery component in the application.<br />

\*\* Install from Extensions- Angular snippets (by John Papa)<br />
Angular files<br />
Angular language service - intellisense<br />
Auto Rename Tag - auto rename end tag when renaming start of tag.<br />
Bracket pair colorizer - color the methods to identify start and end.<br />
debugger for chrome -<br />
Material Icon theme<br />
Prettier - code formatter to format javascript, type script<br />
TSLint - highlight/ notify when coding when doing something wrong.<br />
angular2-switcher - switch between files using shortcuts.<br />
\*\* <ng g c COMPONENT-NAME> -- create a component in the project. Remember to navigate to the app folder before running this command.<br />
\*\* <ng g guard auth --SkipTest> -- add guard to the application.<br />

### Steps to use github:
Install git bash into your local system.<br />
Then set user name and email id in git bash.<br />
Restart application.<br />
** < git init> initialize a git repository for the complete project.<br />
** < git remote add origin https://github.com/PranayShandil/DatingApp.git> push the whole project to new repository<br />
\*\* <git push -u origin master> push files to git from terminal window.(this will sync local checkin to github repository)<br />
