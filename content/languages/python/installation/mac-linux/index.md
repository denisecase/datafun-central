---
title: "Python: Mac/Linux"
---

## Task 1 - Install Python

1.  Open a terminal window
2.  Run the following command to install Python:
    1.  `sudo apt-get install python3`
    2.  (for Debian/Ubuntu-based systems) or
    3.  `brew install python3`
    4.  (for macOS)

## Task 2 - Install pip

pip is the default package manager for Python used to install, update, 
and manage Python packages and dependencies. 

1.  Open a terminal window
2.  Run the following command to install pip:
    1.  `sudo apt-get install python3-pip`
    2.  (for Debian/Ubuntu-based systems) or
    3.  `sudo easy_install pip`
    4.  (for macOS)

## Task 3 - Verify

1.  Open a terminal window
2.  Run the following commands to verify installation:

```shell
python3 --version
pip3 -- version
```

or 

```shell
python --version
pip --version
```

If you see version information, the installation was successful.

You may need multiple Python versions available on your machine, 
depending on the requirements of your project and the external tools and 
libraries required. 