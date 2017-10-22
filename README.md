# esp32-smbus

## Introduction

This component provides a subset of the System Management Bus (SMBus) version 3.0 protocol, used to communicate with SMBus-compatible devices
over a 2-wire I2C bus. Only 7-bit I2C addresses are currently supported. SMBus PEC is not supported.
 
It is written and tested for the [ESP-IDF](https://github.com/espressif/esp-idf) environment, version 2.1, using the xtensa-esp32-elf toolchain (gcc version 5.2.0).

## Dependencies

...

## Example

An example of this component in use can be found at [DavidAntliff/esp32-tsl2561-example](https://github.com/DavidAntliff/esp32-tsl2561-example)

## Features

...

## Documentation

Automatically generated API documentation (doxygen) is available [here](https://davidantliff.github.io/esp32-smbus/index.html).

## Source Code

The source is available from [GitHub](https://www.github.com/DavidAntliff/esp32-smbus).

## License

The code in this project is licensed under the MIT license - see LICENSE for details.

## Links

 * [System Management Bus (SMBus) Specification, version 3.0](http://www.smbus.org/specs/SMBus_3_0_20141220.pdf)
 * [I2C-bus Specification and User Manual](https://www.nxp.com/docs/en/user-guide/UM10204.pdf)
 
## Acknowledgements

 * "I2C" is a registered trademark of Phillips Corporation.
 * "SMBus" is a trademark of Intel Corporation.

## Roadmap

The following features are anticipated but not yet implemented:

 * 10-bit I2C addresses
 * SMBus Packet Error Checking (PEC)

