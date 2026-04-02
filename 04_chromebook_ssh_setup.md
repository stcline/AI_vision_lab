# Using SSH from a Chromebook

This guide explains how to connect to a Raspberry Pi from a Chromebook when you do not have a monitor, keyboard, or mouse available.

## What SSH Does

SSH lets you connect to the Raspberry Pi over a network and control it from another device using a command-line interface.

## What You Need

- A Raspberry Pi connected to the network.
- SSH enabled on the Raspberry Pi.
- The Raspberry Pi’s IP address or hostname.
- A Chromebook with an SSH client or terminal access.

## Enable SSH on the Pi

Before connecting from a Chromebook, SSH must be turned on on the Raspberry Pi. One common way is to enable it from the Raspberry Pi configuration tool.

```bash
sudo raspi-config
```

Then navigate to the SSH option and enable it.

## Find the Pi’s Address

You will need the Raspberry Pi’s IP address so the Chromebook knows where to connect.

Helpful commands:
```bash
hostname -I
ip address
```

## Chromebook Connection Options

Chromebooks can use:
- The built-in Linux terminal, if available.
- A Secure Shell app or extension.
- Another SSH client approved by your district.

Helpful tutorials and references:
- [Connect to the Raspberry Pi from a Chromebook](https://www.everydaylinuxuser.com/2014/03/connect-to-raspberry-pi-from-hp.html)
- [SSH connection via Chrome Secure Shell extension](https://forums.raspberrypi.com/viewtopic.php?t=308351)
- [Setting up port forwarding with Chromebook SSH](https://www.youtube.com/watch?v=A8vUz5jkXJc)

## Example Connection

```bash
ssh pi@192.168.1.25
```

Replace the IP address with your Raspberry Pi’s actual address.

## Classroom Use Case

SSH is especially helpful when you are short on equipment or when you want students to work remotely from lightweight laptops. It also supports headless setups in labs and shared classrooms.
