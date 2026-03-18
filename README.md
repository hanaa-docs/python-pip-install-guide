# How to Install a Python Package Using pip (Beginner Guide)

## Overview

`pip` is Python’s package installer. It is used to download and install packages (also called libraries), which add extra features to Python.

This guide explains how to install a Python package using `pip` and verify that the installation was successful.

## Before You Start

Before following this guide, make sure:

- Python is installed on your computer
- You can open **Command Prompt** on Windows

> Run the commands in this guide in **Command Prompt**, not in the Python interpreter window (`>>>`).

If you have not installed Python yet, refer to the Python installation guide.

## Check That Python Is Installed

1. Open **Command Prompt**.
2. Run the following command:

```bash
python --version
```

You should see the installed Python version.

Example output:

```bash
Python 3.13.12
```

## Check That pip Is Available

1. In **Command Prompt**, run:

```bash
pip --version
```

You should see the installed `pip` version.

Example output:

```bash
pip 25.x from ...
```

> `pip` is usually installed automatically with modern versions of Python.

## Install a Python Package

1. In **Command Prompt**, run:

```bash
pip install requests
```

In this command:

- `pip` is the package installer
- `install` tells `pip` to install a package
- `requests` is the package name

`pip` will download and install the package automatically.

## Verify the Installation

To confirm that the package was installed successfully, run:

```bash
pip show requests
```

If the installation was successful, the output should display package details such as:

- Name
- Version
- Summary
- Homepage
- Author
- License

## Common Beginner Errors

- **`Python was not found`**  
  Make sure Python was installed correctly and that you selected **Add Python to PATH** during installation.

- **`pip is not recognized`**  
  `pip` is usually installed automatically with modern versions of Python. If this error appears, Python may not have been added to PATH correctly.

- **Wrong terminal / command prompt issue**  
  Run the commands in **Command Prompt** on Windows, not in the Python interpreter window (`>>>`).

## Commands Used in This Guide

```bash
python --version
```

Checks which Python version is installed.

```bash
pip --version
```

Checks whether `pip` is installed and shows its version.

```bash
pip install requests
```

Installs the package named `requests`.

```bash
pip show requests
```

Shows details about the installed `requests` package.

## Conclusion

Installing packages with `pip` is a basic but important Python skill. It allows beginners to add extra tools and libraries to Python for future projects.

Learning how to use `pip` is a strong first step toward working with Python more confidently..
