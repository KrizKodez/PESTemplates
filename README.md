# PESTemplates
PowerShell template files to kick off with scripting in a standardized form.

## Motivation
The templates are a good starting point for working in a team and later perhaps in a larger audience to build a unified code base. Through the defined structure and formatting it is easier to read, debug or adapt other people's code. The defined metadata captures important data about the code and allows the automated creation of a script catalog. The creation of a lightweight function library is also supported, which can avoid the much more complex creation of PowerShell modules.

## Description
In principle, we differentiate between two types of scripts, Controller scripts and Tool scripts.

| Type | Templates |
|------|------------|
| Controller | [ControllerWithFunctionsName].ps1
| | [ControllerWithoutFunctions].ps1
| Tool | [PrivateLibraryCallerScriptName].ps1
| | [PublicLibraryName].[CompanyName].ps1

Controllers are the frontend of a PowerShell solution, the workhorse, so to speak, this is where the task is defined and solved. Tool scripts provide support in the form of functions, scriptblocks or modules, they are loaded and used by the controllers.

### [ControllerWithFunctionsName].ps1
This template is used if the controller is structured through usage of functions which reside inside the script. It uses a function called Main (like in other programming languages) as visible entry point for the code execution. Because of the fact that the Main function is the first function in the script it avoids searching and/or scrolling where the script starts.

### [ControllerWithoutFunctions].ps1
This template is the simplest one and should be used for relative short scripts without functions inside.



## Contributing
All Administrators which using PowerShell are very welcome to help and make the templates better, more useful or contribute new ideas.


## License

This project is licensed under the terms of the GPL V3 license. Please see the included Licence.txt file for more details.
