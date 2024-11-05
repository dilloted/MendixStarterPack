# MendixStarterPack
A set of helpful scripts that can get you moving on the first day of work.

Make your first day a piece of cake when using this quick little script. It couldnt be easier to get started,
pull down this GitHub repo and get it going!

# Windows

Start with getting Choco (The package manager for Windows)
 
Enter PowerShell as Administrator
 
Run "Get-ExecutionPolicy" . If it returns Restricted, then run "Set-ExecutionPolicy AllSigned"
 
Run the following command:
 
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
 
This command will install chocolatey. You can now run and install packages safely on your machine. 

Navigate to the /windows folder and run install.ps1

# Mac

Start with getting Brew! The package manager for Mac

Enter terminal and run the following



# Docker

Follow the guide set here! Thanks to the Mendix team for making this install quick and easy

https://github.com/mendix/docker-mendix-buildpack
