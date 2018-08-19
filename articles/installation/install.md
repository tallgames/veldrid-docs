---
uid: installation
---

# Installation
Veldrid is build on .NET Standart 2.0, so it requires .NET Core to be installed on your device. This tutorial is done using MS Visual Studio 2017 and Windows 10 PC but it is also available to do the same thing on other Windows versions. It is built with .NET Full. To build your own Veldrid project follow these instructions:
1. Download and install .NET Core 2.1 from Microsoft official website [here](https://www.microsoft.com/net/download)
2. Reboot your PC
3. Start Visual Studio 2017
4. Press *Create project* or *More project templates...*
5. Create Console Application
6. Open *View->Other Windows->Package Manager Console*
7. Type `Install-Package Veldrid` in the console and press ENTER
8. If everything is done correctly you will have Veldrid references in your project
Don't forget to add namespace usage definitions to your code.
