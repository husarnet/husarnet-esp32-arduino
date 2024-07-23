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

Coming soon...

## Examples

You'll find full examples in our [examples](examples) directory.

Start with a [simple-webserver](examples/simple-webserver) for a fairly minimal example.
