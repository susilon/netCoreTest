# netCoreTest
For testing .net core web application devops.

Require :

for deployment
- Linux Server or Windows Server
- Docker

for development
- Visual Studio 2017 or newer
- .Net Core

Step :
- Copy files to target machine
- run docker build -t netCoreTest .
- run docker run -d -p 8080:80 --name netcoretest netCoreTest
- open in browser : serveraddress:8080

Change log :
2019-12-27 : 
- upgraded to .NetCore.App v2.2
- upgraded to AspNetCore.All v.2.2.8