# 🍫 Chocolatey Menu
## 📋 Description
Chocolatey Menu is a PowerShell script initially created to facilitate my work in IT. Its main objective is to simplify and speed up the mass installation of applications using [Chocolatey](https://chocolatey.org/)
 on Windows systems. This intuitive menu helps users effortlessly select apps to install, update, or delete.

## 🌟 Features
- 🍫 Chocolatey Check & Install: Checks and installs Chocolatey if not already present on the system.
- 📝 Installed Apps Display: Showcases a list of all the apps installed through Chocolatey.
- ⬆️ Update All Apps: Provides an option to update all Chocolatey-installed applications at once.
- ❌ Uninstallation: Allows the removal of selected applications.
- 🔄 Self-update: Checks and updates the script to its latest version if available.

## 🚀 How to Use
- Launch the Script: Use run.bat to initiate the Chocolatey_Menu.ps1 script.
- Select Applications: The menu presents a list of applications. Choose the ones you wish to install by marking them with 'x'.
- Additional Options:
    - E. Execute selected installations.
    - L. List all Chocolatey-installed applications.
    - D. Remove applications.
    - U. Update all Chocolatey applications.
    - S. Exit the menu.

## 🔗 Sample Applications List
In the provided script, applications like "googlechrome" and "vscode" are mere examples. Feel free to expand, replace or customize this list to your needs. Add more apps to the $global:apps list in the script as needed, you can check the list of apps in [Chocolatey Packages](https://community.chocolatey.org/packages)
