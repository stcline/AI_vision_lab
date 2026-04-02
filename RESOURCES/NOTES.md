## Testing 
- Try out [these python scripts](https://github.com/automaticdai/rpi-object-detection/tree/master).
- Try [these tests](https://www.raspberrypi.com/documentation/accessories/ai-camera.html#pose-estimation).
- Fill out [this form](https://docs.google.com/forms/d/e/1FAIpQLSf0kHy8g-mznL2xY-hj0RAH6xDRZzN5P4Wu5LjMrAHdAA8UNQ/viewform?usp=dialog) when you are done.

## Concept (include a presentation for teachers to reference)

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
