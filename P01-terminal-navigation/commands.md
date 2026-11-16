# P1 — Project folder and terminal navigation

## Goal
Create a project folder and practise moving around it using terminal commands.

## macOS / Linux / Git Bash
```bash
mkdir web-development
cd web-development
mkdir portfolio
cd portfolio
pwd
ls
touch index.html style.css
ls
cd ..
pwd
```

## Windows PowerShell
```powershell
mkdir web-development
cd web-development
mkdir portfolio
cd portfolio
Get-Location
Get-ChildItem
New-Item index.html -ItemType File
New-Item style.css -ItemType File
Get-ChildItem
cd ..
Get-Location
```

## Useful commands
- `pwd` / `Get-Location`: show current folder
- `ls` / `Get-ChildItem`: list files
- `cd folder-name`: enter a folder
- `cd ..`: move one folder up
- `mkdir name`: create a folder
- `touch file` (or `New-Item`): create a file
