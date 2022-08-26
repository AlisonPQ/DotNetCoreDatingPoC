# DotNetCoreDatingPoC

## Useful commands

`dotnet --info` to see dotnet information

`dotnet -h` to see available commands to use, for example `dotnet new -h`

`dotnet run` inside the projet to run and make sure the project runs

Trusting the HTTPS development certificate
`dotnet dev-certs https --trust`

To watch what is happening (keep an eye) on terminal run:

`dotnet watch run`

### To create a new project

To have a project container

`dotnet new sln`

`dotnet new webapi -o API`

To add a project into a solution `sln` use:

`dotnet sln add API`

## Access Modifiers

### Public

Public means that this property can be get or set from any other class in our application and same goesfor the class itself

### Protected

Protected means that this property can be accessed from either this class or any classes that inheritfrom this class

### Private

Private that means that this property is only accessible from inside this class itself

## Tips

* Set auto save `File -> Auto Save`
* Excluding folders like "obj", "bin" -> `Code -> Preferences -> Settings -> Type 'exclude' -> Search for 'Files: Exclude' section -> Click on Add Pattern [**/obj]`
* Set Compact Folders `Code -> Preferences -> Settings -> Type 'folder' -> Search for 'Explorer: Compact Folders' section -> Uncheck checkbox`

## Setting Up Visual Studio to work with `C#`

Install the following extentions:

* C#

``` text
Name: C#
Id: ms-dotnettools.csharp
Description: C# for Visual Studio Code (powered by OmniSharp).
Version: 1.25.0
Publisher: Microsoft
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp
```

* C# Extentions

``` text
Name: C# Extensions
Id: kreativ-software.csharpextensions
Description: C# IDE Extensions for VSCode
Version: 1.7.1
Publisher: JosKreativ
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=kreativ-software.csharpextensions
```

* Material Icon theme

``` text
Name: Material Icon Theme
Id: PKief.material-icon-theme
Description: Material Design Icons for Visual Studio Code
Version: 4.20.0
Publisher: Philipp Kief
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
```
