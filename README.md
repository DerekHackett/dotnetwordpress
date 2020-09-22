# DotNetWordPress

This repo is an example of running WordPress on .net core. There is no PHP installed or running. You just have to setup a database to use and fire up the code. 

This is made possible using 

[PeachPie](https://www.peachpie.io/)

and

[GitHub](https://github.com/iolevel/wpdotnet-sdk)

## Setting Up Database

You can use any MySQL database for this but the easiest way is to run the database in a docker container.

> docker pull mysql

> docker run -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=wordpress -p 3306:3306 -d mysql

## Running the Project

> dotnet run
