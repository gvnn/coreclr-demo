.NET Hello World on on OS X
===========================

## Install

[https://github.com/dotnet/coreclr/blob/master/Documentation/install/get-dotnetcore-dnx-osx.md](https://github.com/dotnet/coreclr/blob/master/Documentation/install/get-dotnetcore-dnx-osx.md)

## Run

To list all the DNXs

	dnvm list

Pick Mono DNX and restore packages

	dnvm use 1.0.0-beta7-12255 -r mono
	dnu restore

run app with .NET Core

    dnvm use 1.0.0-beta7-12255 -r coreclr
	dnx . run