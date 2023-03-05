---
layout: default
title: Mac-Linux
---
# Mac/Linux Installation

## Task 1 - Download and install Git

1.  Open a terminal window
2.  Run the following command to install Git:
    *   `sudo apt-get install git`
    *   (for Debian/Ubuntu-based systems) or
    *   `brew install git`
    *   (for macOS)

## Task 2 - Configure Git

1.  Open a terminal window
2.  Run the following commands to configure Git <span>with your name (your real name, e.g. "Denise Case") and the email address you used for GitHub:</span>

  ```
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```

3.  Important: Replace "Your Name" with your name and "[your.email@example.com](mailto:your.email@example.com)" with the email address associated with your GitHub account
4.  This configuration will be used for all of your Git repositories

## Task 3 - Verify

1. Run the following command to verify your Git configuration:

```
git config --list
```

2.  You should see your name and email address listed under the "user" section
3.  If the information is not correct, you can run the `git config` command again to update it
