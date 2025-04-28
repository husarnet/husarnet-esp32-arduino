![Husarnet logo](images/logo.svg)

# Husarnet for Arduino ESP32

Husarnet is a low latency, lightweight, privacy preserving P2P VPN. If you want
to know more go to the [Husarnet's webpage](https://husarnet.com/) or directly
to the [documentation page](https://docs.husarnet.com/).

This repository only contains library code for the Arduino IDE. If you want
to use Husarnet with the PlatformIO IDE, go to the [husarnet-esp32-platformio](https://github.com/husarnet/husarnet-esp32-platformio).

Due to the way precompiled libraries work in Arduino the static library for each
target must be placed in a seperate directory. Due to this `libhusarnet.a` is
duplicated few times in different folders.

## Installation and usage

This library is available through the [Arduino Library Manager](https://docs.arduino.cc/software/ide-v2/tutorials/ide-v2-installing-a-library/).

The quick-start guide and FAQ is provided in the [Husarnet ESP32 documentation](https://husarnet.com/docs/esp32-arduino/) to help you get started.

## Examples

You'll find full examples in our [examples](examples) directory.

Start with a [simple-webserver](examples/simple-webserver) for a fairly minimal example.
