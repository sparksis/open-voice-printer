# Voice Assistant Printer

## Goals

Provide a simple voice interface which can send print jobs to a configured printer.

Voice jobs may include the following:

* Creation of expirely labels for refrigerated items.

## Design

### Hardware

The only component other than a [CUPS](https://www.cups.org/) device should be a RaspberryPi or other low powered print server.

### Software

The Software should adhere to the UNIX Philosify
[Do One Thing and Do It well](https://en.wikipedia.org/wiki/Unix_philosophy#Do_One_Thing_and_Do_It_Well).
Multiple modules should be built that can interconnect but are not explicitly dependant on each other.

#### Diagram

TODO...
