+++
title = "VS Code"
weight = 40
+++

Visual Studio Code (VS Code) is a popular code editor that supports many programming languages, including PowerShell. 


## Terminals in VS Code

1. Open VS Code and navigate to the "Terminal" panel by clicking on the terminal icon in the left-hand panel, or by using the keyboard shortcut `Ctrl+Shift+` ``.

2. In the Terminal panel, click on the plus (+) icon to open a new terminal.

## Default Shell

By default, the new terminal will use the default shell associated with your system, e.g., Windows Command Prompt (cmd).

## Open a PowerShell Terminal from Panel

To open a PowerShell terminal in VS Code, click on the drop-down arrow in the terminal panel and select "PowerShell" from the list of available shells.

## Set Default Terminal

There are several options for setting the default terminal to PowerShell in VS Code:

1. Use the Command Palette (recommended)
1. Use the Terminal Dropdown
1. Use the VS Code Settings

### 1. Set Default using Command Palette (Recommended)

This method helps with multiple PowerShell installations when you want to open a specific PowerShell option. 

In VS Code, from the menu, select View / Command Palette / Terminal: Select Default Profile.

Look carefully at the PowerShell options. For example, you may have:

- PowerShell
- Winddows PowerShell 

the typical installation path for PowerShell Core is something like C:\Program Files\PowerShell\7.

The typical installation path for Windows PowerShell is something like C:\Windows\System32\WindowsPowerShell\v1.0.

[Read more about Windows PowerShell vs PowerShell Core]({{< relref "core.md" >}}).

### 2. Set Default from Terminal Dropdown

Alternatively, to make PowerShell your default terminal in VS Code, click on the drop-down arrow in the terminal panel and select "Select Default Profile".

1. In the "Select Default Profile" dropdown, select "PowerShell" from the list.

### 3. Set Default using Settings

Or to configure the Settings directly, follow these steps:

1. Open the VS Code settings editor by clicking on the gear icon in the lower-left corner of the window and selecting "Settings" from the menu.

2. In the search bar at the top of the settings editor, type "terminal.integrated.shell.windows". This will filter the settings to show the terminal shell settings for Windows.

3. Click on the edit icon (pencil icon) next to "Terminal > Integrated > Shell: Windows" to open the editing interface.

4. Enter the path to the PowerShell executable that you want to use as the default shell in VS Code. For example, if you want to use PowerShell Core (the cross-platform version), you might enter "C:\Program Files\PowerShell\7\pwsh.exe" (assuming that PowerShell Core is installed in the default location).

5. Save the changes to the "Settings" editor by clicking on the "Save" button or using the keyboard shortcut (Ctrl+S on Windows/Linux or Command+S on macOS).

## Run PowerShell as Administrator

Sometimes you'll need to run PowerShell as an Adminstrator (Admin), 
for example, when installing packages with Chocolatey. 

Outside VS Code, Start / Windows PowerShell / Run as Administrator. 

Use as needed and then return to VS Code for non-admin commands. 