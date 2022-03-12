# Eau Claire Salon Scheduler Web Application

#### By Anastasia Han 

#### _Web application for salon administration staff to manage client and stylist database._

## Technologies Used

* _HTML_
* _Razor_
* _CSS_
* _C#_
* _MySQL Workbench_
* _.NET_
* _ASP.NET_
* _Entity_
* _SQL_

## Description

_This web application was made for salon administration to keep track of stylists and respective clients._

## Setup/Installation Requirements

### Your computer will need to have the following installed and set up:
* _[GIT](https://docs.github.com/en/get-started/quickstart/set-up-git)_
* _[Visual Studio Code](https://code.visualstudio.com/download)_
* _[Node](https://nodejs.dev/learn/how-to-install-nodejs)_
* _.NET - [Mac](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.401-macos-x64-installer) or [Windows](https://dotnet.microsoft.com/download/dotnet/thank-you/sdk-5.0.401-windows-x64-installer)_
* _[MySQL Workbench](https://dev.mysql.com/downloads/file/?id=484391)_


### File Setup

* _Once you have VSCode, Node, and GIT set up, you will need to open up your terminal, navigate to your Desktop and type the command:_
git clone https://github.com/1ana-banana/EauClairesSalon.Solution.git 

* _Open a new terminal in VSCode. Navigate to_ EauClairesSalon.Solution > HairSalon _and type the following command:_ touch appsettings.json
* _Copy and paste the following code into the new file:_
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=anastasia_han ;uid=root;pwd=[YOUR PASSWORD];"
  }
}
* _Input your own password into: _ [YOUR PASSWORD]
* _Open MySQL Workbench and select Data Import/Restore from the Navigator/Administration tab, then select Import from Self-Contained File in Import Options to import the included database in the repo. You will then select the New button under default Schema to be imported. Enter the name of your database and click ok. Navigate to the Import Progress tab and click Start Import. Click refresh all.
* _Enter_ dotnet watch run _into the terminal. Navigate to_ http://localhost:5000 _in the browser_


## Known Bugs

* _No known issues_

## License

_If you encounter any issues or would like to reach out, email [anastasia.han@yahoo.com](mailto:anastasia.han@yahoo.com)._

MIT License

Copyright (c) 2022 Anastasia Han 
