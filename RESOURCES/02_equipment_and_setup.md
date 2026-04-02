# Equipment and Setup

This guide covers the basic hardware and software needed to begin AI vision work with a Raspberry Pi.

## Required Equipment

| Item | Recommendation | Link | Notes |
|---|---|---|---|
| Raspberry Pi | Raspberry Pi 5, 8GB RAM | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+5+8GB) | Recommended starting point for AI vision work because it has more memory and better performance than older Pi models. |
| Power Supply | Official Raspberry Pi 27W USB-C Power Supply for Raspberry Pi 5 | [Amazon search](https://www.amazon.com/s?k=Official+Raspberry+Pi+27W+USB-C+Power+Supply) | Use the official supply for best reliability and stable power delivery. |
| microSD Card | At least 32GB, Class 10 or better | [Amazon search](https://www.amazon.com/s?k=32GB+microSD+card+Class+10) | A larger card gives room for the OS, updates, and project files. |
| Camera | Raspberry Pi Camera Module 3 | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+Camera+Module+3) | Official camera module recommended for beginner and classroom AI vision projects. |

## Optional Equipment by Upgrade Level

| Upgrade Level | Item | Link | Why It Helps |
|---|---|---|---|
| Better Pi | Raspberry Pi 5, 16GB RAM | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+5+16GB) | More memory can help with heavier software, larger models, or multiple browser tabs. |
| Better Storage | 64GB or 128GB microSD card | [Amazon search](https://www.amazon.com/s?k=128GB+microSD+card+Class+10) | More storage for models, logs, images, and student files. |
| Better Camera | Raspberry Pi Camera Module 3 Wide | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+Camera+Module+3+Wide) | Wider field of view can help in classroom demos and tracking projects. |
| Better Cooling | Raspberry Pi 5 case with active cooler | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+5+case+active+cooler) | Helps reduce throttling during longer AI vision runs. |
| Starter Electronics Kit | Raspberry Pi starter kit with breadboard, jumper wires, LEDs, resistors, and sensors | [Amazon search](https://www.amazon.com/s?k=Raspberry+Pi+starter+kit+breadboard+jumper+wires+LEDs+sensors) | Gives students a ready-to-use electronics set for motion, indicator, and automation projects. |
| USB Camera | USB webcam compatible with Raspberry Pi | [Amazon search](https://www.amazon.com/s?k=USB+webcam+compatible+with+Raspberry+Pi) | Useful as a backup camera or for projects where a USB camera is easier to mount. |
| External Storage | USB SSD or flash drive | [Amazon search](https://www.amazon.com/s?k=USB+SSD+for+Raspberry+Pi) | Helpful when storing many images, videos, or larger project files. |

## Basic Setup Steps

1. Install Raspberry Pi OS using the official Raspberry Pi Imager instructions: [Raspberry Pi software](https://www.raspberrypi.com/software/).
2. Insert the microSD card into the Raspberry Pi.
3. Connect the camera following the official camera setup guidance: [Camera documentation](https://www.raspberrypi.com/documentation/accessories/camera.html).
4. Connect the official power supply and power on the device. Raspberry Pi’s getting started guide covers initial setup and power-on steps: [Getting started](https://www.raspberrypi.com/documentation/computers/getting-started.html).
5. Complete the first boot setup and confirm the system reaches the desktop or command line.
6. Update the system:

```bash
sudo apt update
sudo apt upgrade
```

7. Reboot if needed:

```bash
sudo reboot
```

## Classroom Setup Notes

For a classroom, it helps to build one “master” image first and then clone it to other SD cards. Raspberry Pi Imager is the official tool for writing OS images to microSD cards, and it can also be used to preconfigure settings before first boot: [Raspberry Pi software](https://www.raspberrypi.com/software/).

A useful workflow is:
- Configure the Pi once with the correct timezone, username, and Wi-Fi settings.
- Test camera access and any needed libraries.
- Save the image and reuse it across student kits.

## Tutorials for Cloning and Deployment

These resources are useful for creating a reusable classroom image and deploying it to multiple SD cards:

- [Raspberry Pi Imager](https://www.raspberrypi.com/software/)
- [Getting started with Raspberry Pi](https://www.raspberrypi.com/documentation/computers/getting-started.html)
- [Setting up your Raspberry Pi](https://projects.raspberrypi.org/en/projects/raspberry-pi-setting-up)

Raspberry Pi Imager is especially useful because it can pre-set Wi-Fi, username, password, and SSH options before the first boot, which is ideal for classroom deployment.

## Good Practices

- Keep a checklist for each kit.
- Test the camera before 
