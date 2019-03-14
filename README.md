# boxstarter
miho's data demo environment

# How to Use
## Install Chocolatey
Launch PowerShell prompt with "Run as Administrator".

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Install Boxstarter
Execute the following command on PowerShell.

```powershell
CINST -y Boxstarter
```

## Execute desktopscript!
Execute the following command on PowerShell.

```powershell
BOXSTARTERSHELL
Install-BoxstarterPackage -PackageName 
```
