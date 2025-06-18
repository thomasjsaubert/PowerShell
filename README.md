![PowerShell Banner](https://www.fullstackpython.com/img/logos/powershell.png)

Welcome to my PowerShell project! This is a beginner-friendly guide to what PowerShell is, what it can do, and a few practical examples to help you get started.

---

## 🧾 What is PowerShell?

PowerShell is a **command-line shell and scripting language** built on the .NET framework. It's designed to help IT professionals and system administrators automate tasks, configure systems, and manage computers more efficiently.

---

## 🛠️ What Can PowerShell Do?

PowerShell can:

- Automate repetitive tasks like user creation or file cleanup
- Manage system services, files, and processes
- Access Windows Registry and Event Logs
- Schedule tasks and run background jobs
- Interact with cloud platforms like Microsoft Azure

---

## 🔁 Common PowerShell Commands

| Command | Description |
|---------|-------------|
| `Get-Help` | View help documentation for any command |
| `Get-Command` | List all available PowerShell commands |
| `Get-Process` | Show running processes |
| `Get-Service` | View the status of services on the system |
| `Set-ExecutionPolicy` | Change script execution policy |
| `Get-EventLog` | View system event logs |

---

## 🧪 Sample Script

This sample script demonstrates how to create a folder, a file, and add text to it using PowerShell.  
You can find the script here: [`Create-Folder-And-File.ps1`](scripts/Create-Folder-And-File.ps1)

### Preview:

```powershell
# Create a new directory
New-Item -ItemType Directory -Path "C:\PowerShellDemo"

# Create a new text file inside the folder
New-Item -ItemType File -Path "C:\PowerShellDemo\example.txt"

# Write text into the file
Set-Content -Path "C:\PowerShellDemo\example.txt" -Value "Hello, this was created with PowerShell!"
