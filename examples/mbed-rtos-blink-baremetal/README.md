How to build PlatformIO based project
=====================================

1. [Install PlatformIO Core](http://docs.platformio.org/page/core.html)
2. Download [development platform with examples](https://github.com/platformio/platform-siliconlabsefm32/archive/develop.zip)
3. Extract ZIP archive
4. Run these commands:

```shell
# Change directory to example
$ cd platform-siliconlabsefm32/examples/mbed-blink-baremetal

# Build project
$ pio run

# Upload firmware
$ pio run --target upload

# Build specific environment
$ pio run -e efm32gg_stk3700

# Upload firmware for the specific environment
$ pio run -e efm32gg_stk3700 --target upload

# Clean build files
$ pio run --target clean
```