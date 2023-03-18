+++
title = "Configuration"
+++

After installing, configure Git with your name and email. 

Use your GitHub email for best results.

## Open Git Bash on Windows

To open Git Bash on Windows:

1. Press the Windows key on your keyboard to open the Start menu.
1. Type "Git Bash" into the search bar and select it from the list of results.
1. Git Bash should now open in a new window.


## Open Terminal on Mac or Linux

On Mac or Linux, open Terminal app.

## Check Git Configuration

Type the following command to display your Git configuration:

```bash
git config --list
```

Look for the following lines in the output:

```
user.name=Your Name
user.email=your.email@example.com
```

If you see your name and email listed, then they are set in Git.

## Set Git Configuration

If you don't see your name and email listed, 
set them using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email your.email@example.com
```

Replace "Your Name" and "your.email@example.com" with 
your actual name and 
email address. 

The `--global` flag ensures the settings are applied globally 
across all your Git repositories.
