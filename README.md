# setup-windows-chocolatey
Script for setup windows developer environment with chocolatey

## Requirements
Chocolatey

## Get Started

The first step is install the chocolatey, you can do this by powershell in administration mode using the command below
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

After this is only run the command line below to install all packages
```
choco install openjdk12 --version 12.0.2.1 -y; choco install nodejs.install --version 19.2.0 -y; choco install python --version 3.11.0 -y; choco install vscode --version 1.73.1 -y; choco install intellijidea-community --version 2022.3 -y; choco install git --version 2.38.1 -y; choco install pycharm-community --version 2022.3 -y
```

With this you will have installed
  - OpenJDK 12.0.2.1
  - Node JS 19.2.0
  - Python 3.11.0
  - VSCode 1.73.1
  - Intellij 2022.3
  - Pycharm 2022.3
  - Git 2.38.1
