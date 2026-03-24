## Setting up the Raspberry Pi
Before you begin running your camera, you need to prepare the Pi:
1. update and upgrade
  `sudo apt update && sudo apt full-upgrade`
2. Install the IMX500 firmware
  `sudo apt install imx500-all`
3. Clone this repository
4. Create an authentication token
6. Cache your credentials
  `sudo git config --global credential.helper cache`
