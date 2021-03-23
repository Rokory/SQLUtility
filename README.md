# SQLUtility

## Requirements

Requires the module BitsDownload. You can pull it from <https://github.com/Rokory/BITSDownload>

## Getting started

It is recommended to copy the folders in Modules to one of the folders indicated by the $env:PSModulePath variable (e. g. %userprofile%\Documents\WindowsPowerShell\Modules).

First, import the module.

````powershell
Import-Module SQLUtility
````

You can either use the module name or the full path, if you did not copy the module to one of the paths in $env:PSModulePath.

To find information about useage, use ```Get-Help``` followed by the cmdlet in the module

## Install-SqlServer

Downloads and optionally installs SQL Server 2019 Developer or Express editition. Demonstrates the support of the -WhatIf parameter.

## Install-SqlServerManagementStudio

Downloads and installs SQL Server Management Studio 18.4.

## Connect-SqlServer, Invoke-SqlCommand, New-SqlDatabase, Get-SqlDataReader

Demonstrate useful patterns for working with SQL databases in PowerShell.
