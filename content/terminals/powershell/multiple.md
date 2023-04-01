+++
title = "PowerShell: Multiple Versions"
weight = 30
+++

There may be multiple versions of PowerShell on your computuers, especially on Windows. 
This can sometimes cause confusion. 

It's perfectly fine to have multiple installations, but you can remove some if they are unneeded. 

On Windows machines, it's common to have both:

- PowerShell Core (the newer, cross-platform version)
- Windows Powershell (the original Windows-specific verison)

[Read more about Windows PowerShell vs PowerShell Core]({{< relref "core.md" >}}).

## Uninstall

To uninstall older versions of PowerShell on Windows, follow these steps:

1. Open the Start menu and type "Add or remove programs" in the search box. Click on the "Add or remove programs" option that appears in the search results.

1. In the list of installed programs, locate the PowerShell versions to uninstall. Search for "PowerShell" or sort the list by name or date to find the relevant entries.

1. Click on each PowerShell version that you want to uninstall, then click "Uninstall". Follow the prompts to complete the process.

1. Once uninstalled, ensure the version you want to keep is still installed and functional.

1. Check the version of PowerShell by opening a PowerShell window and running the command $PSVersionTable.PSVersion. This will display the version number of the PowerShell installation that is currently in use.