# arduino-idf-sample
Basic configuration of latests ESP-IDF 4.4 building with the latest Arduino-ESP32 master commit.

## How to use
1. Follow instructions for installing the IDF from espressif docs
[https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html#step-1-install-prerequisites]
2. Make sure your environment paths are set correctly.
3. Clone this project `git clone --recursive git@github.com:intake-health/arduino-idf-sample.git`
4. Open a command window and navigate to the project. Run `idf.py build` and flash to your device.

## Includes
The documentation wasn't very clear for how to get these two in development, but seem to be nearing maturity projects to work together to use Arduino packages with the latest ESP-IDF. As of writing the release/4.4 branch works with the master branch of arudino-esp32. This project is a snapshot (I think) of today's build that is working.
