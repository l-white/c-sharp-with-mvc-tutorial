# MVC Tutorial in C#
This tutorial demonstrates how to create a simple MVC application in C# with Razor Views.

For this tutorial, we will use Visual Studio Code.
[Instructions to download]

## 1. Project Setup
Create a folder on your desktop titled calculate-mortgage and drag it into Visual Studio Code.

From the top menu, select Terminal -> New Terminal

Type the following commands into your command line, one at a time:

- dotnet new mvc -o CalculateMortgage
- code -r CalculateMortgage
- dotnet dev-certs https --trust
- If you see a dialog box with the option to add required assets for building and debugging, select Yes to add them.

Now, let's run your app. Type the following into your VS Code terminal to build and run your app:
dotnet run

### Explanation

## 2. Add a Controller
