# Package Management on Raspberry Pi

This file explains the most common ways to install and update software on Raspberry Pi systems.

## Why Package Management Matters

Package management helps you install software, update existing tools, remove unused programs, and keep systems consistent across multiple classroom devices.

## The Two Main Tools

### APT
APT is the standard system package manager used on Raspberry Pi OS and other Debian-based systems. It is commonly used for operating system packages and utilities.

Common examples:
```bash
sudo apt update
sudo apt upgrade
sudo apt install python3-pip
```

### pip
pip is the Python package manager used to install Python libraries from PyPI. It is especially useful for AI and computer vision projects that rely on Python code.

Common examples:
```bash
pip3 install opencv-python
pip3 install numpy
pip3 install mediapipe
```

A good overview of how APT and pip are used on Raspberry Pi is available here:
- [Package management on the Raspberry Pi](https://blog.packagecloud.io/package-management-on-the-raspberry-pi/)

## When To Use Each One

- Use `apt` for operating system software and system-level tools.
- Use `pip` for Python libraries used in your scripts.
- If a project uses both, install system dependencies first, then Python packages.

## Classroom Tips

- Update devices before a lesson begins.
- Keep a list of the packages needed for each project.
- Use the same software version on all kits when possible.
- Document installation steps so students can reproduce them later.

## Example Workflow

1. Update the package list.
2. Install Python tools with `apt`.
3. Install project libraries with `pip`.
4. Test the program.
5. Record the version numbers used.

## Helpful Commands

```bash
sudo apt update
sudo apt upgrade
sudo apt install python3-pip
pip3 --version
```

## Why This Helps Teachers

A predictable package workflow saves time during class and reduces troubleshooting. It also makes it easier to support multiple student groups working on the same project.
