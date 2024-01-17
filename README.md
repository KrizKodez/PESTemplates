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



## Contributing
All Administrators which using PowerShell are very welcome to help and make the templates better, more useful or contribute new ideas.


## License

This project is licensed under the terms of the GPL V3 license. Please see the included Licence.txt file for more details.
