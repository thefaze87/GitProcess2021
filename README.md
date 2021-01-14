# Git Process
My current GitProcess for 2021. Here you will find the code for your `.gitignore` global file, `.bash_profile` global file, and `.inputrc` global file (used for fixing Windows terminal flicker issue)

## Downloads and Resources

### Windows Terminal
- Download **Windows Terminal** https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701
- Microsoft Windows Terminal Github Repo https://github.com/microsoft/terminal (useful information but download from the Microsoft Store - much better).

### Powershell 7
Follow the guide here https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-7 and download the latest Powershell 7 release from Github and install https://github.com/PowerShell/PowerShell/releases/tag/v7.1.0

### Download, Setup, Install Powershell Script for Context Menu Items for Windows Terminal
Adding context menus can be tricky, I tried manually using registry keys and such...didn't turn out right. This does the job really well!
1. Install Windows Terminal
2. Install Powershell 7
3. Launch PowerShell 7 console as administrator, and run `install.ps1` (see below code) to install context menu items to Windows Explorer.
    
    **Quickest way to run the install script with admin / elevated Powershell 7 console**
  
  ```
  Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/lextm/windowsterminal-shell/master/install.ps1'))
  ```

Here's the repo with the details: https://github.com/lextm/windowsterminal-shell

## Bash Profile
Download the `.bash_profile` and install in your `C:\Users\[user]`

## Gitignore
Download the `.gitignore` and install in your `C:\Users\[user]`

## Inputrc (fixes flicker issue with Windows Terminal)
Download the `.inputrc` and install in your `C:\Users\[user]`


# Additional Resources
Learning Git
- https://www.atlassian.com/git
- https://try.github.io/
- https://guides.github.com/introduction/git-handbook/

Git Cheat Sheet
- https://www.git-tower.com/blog/git-cheat-sheet/
- https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet

GUI for Git
- https://www.sourcetreeapp.com/

