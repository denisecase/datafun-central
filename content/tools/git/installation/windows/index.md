---
title: "Windows"
---

## Task 1 - Download and install Git

1. Go to the Git download page at [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Click the "Download" button to download the Git installer
3. Run the installer file that you downloaded
4. Accept the default installation options and click "Install"
5. Choose the appropriate options for line ending conversion and terminal emulator during the installation process

## Task 2 - Configure Git

1. Open a command prompt or PowerShell window
1. Run the following commands to configure Git with your name (your real name, e.g. "Denise Case") and the email address you used for GitHub:

```pwsh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

1. Important: Replace "Your Name" with your name and "[your.email@example.com](mailto:your.email@example.com)" with the email address associated with your GitHub account
1. This configuration will be used for all of your Git repositories

## Task 3 - Verify

1. Run the following command to verify your Git configuration:

```pwsh
git config --list
```

1. You should see your name and email address listed under the "user" section
1. If the information is not correct, run the `git config` command again to update it
