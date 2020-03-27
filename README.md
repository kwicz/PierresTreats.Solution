# _Pierre's Treats_

#### By _**K. Wicz**_


## Description

_An ASP.NET MVC web application to manage a bakery using a many-to-many database structure._

## Program Specifications

| User Stories |
| ------------- |
| All users can view the application landing page, which will feature all available flavors and treats. |
| All users can click treats and flavors on the landing page, and be directed to a new pages which lists all of the treats belonging to that falvor, or vice versa. |
| Authorized users can log in while on the landing page. |
| Authorized users can create, read, update, and delete all flavors in the flavor table of the Pierre's Treats database. |
| Authorized users can create, read, update, and delete all treates in the treats table of the Pierre's Treats database. |


## Setup/Installation Requirements

### 1.  Install .NET Core

#### on macOS:
* [Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.106-macos-x64-installer) to download a .NET Core SDK from Microsoft Corp.

#### on Windows:
* [Click here](https://dotnet.microsoft.com/download/thank-you/dotnet-sdk-2.2.203-windows-x64-installer) to download the 64-bit .NET Core SDK from Microsoft Corp.

#### Install dotnet script
Enter the command ``dotnet tool install -g dotnet-script`` in Terminal (macOS) or PowerShell (Windows).

### 2. Clone this repository

Enter the following commands in Terminal (macOS) or PowerShell (Windows):
```sh
cd desktop
git clone https://github.com/kwicz/PierresTreats.Solution
cd PierresTreats.Solution
```
### 3. Install all necessary packages and make sure the project will build
In your terminal, type the following commands to make sure all necessary packages are included in the project and to launch in your browser:
```sh
cd PierresTreats
dotnet restore
dotnet build
```

### 4. Create the database and tables
Enter the following to build your database and tables for the program:
```sh
dotnet ef migrations add Initial
dotnet ef database update
```

### 5. Launch the project in your browser
In your terminal, type:
```sh
dotnet watch run
```
Then hold ```command``` while clicking the link in your local terminal to your local address, which should be:
```sh
http://127.0.0.1:5000
```

Bon Apetit! The project is now ready to use.

## Known Bugs

_No known bugs at this time._

## Support and contact details

_Have a bug or an issue with this application? [Open a new issue](https://github.com/kwicz/PierresTreats.solution/issues) here on GitHub._

## Technologies Used
* _C#_
* _.NET Core 2.2_
* _ASP.NET Core MVC_
* _MySQL_
* _EF Core 2.2.6_
* _ASP.NET Core Identity_
* _Razor 2.2.0_
* _Material Design Lite_

## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2020 **_K Wicz_**