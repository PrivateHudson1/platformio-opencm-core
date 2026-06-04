# Custom STM32 Arduino Core for OpenCM904

This is a fork of the OpenCM904 core from ROBOTIS, packaged for use with PlatformIO.

## Contents

- `cores/arduino/` - The OpenCM904 core files
- `variants/opencm904/` - Board variant files

## Usage

Add this to your `platformio.ini`:

```ini
platform_packages =
    framework-arduinoststm32 @ https://github.com/PrivateHudson1/platformio-opencm-core.git