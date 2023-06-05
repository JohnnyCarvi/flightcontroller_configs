# Flight Controller Config Repository

Welcome to the Flight Controller Config Repository! This repository is dedicated to storing configuration files for various flight controllers used in my 3D Printed drones.

## Contents

1. [Introduction](#introduction)
2. [Supported Flight Controllers](#supported-flight-controllers)
3. [Usage](#usage)

## Introduction

The configuration files in this repository are intended to assist you in setting up and fine-tuning your 3D Printed drone. A flight controller is a critical component of a drone responsible for processing sensor data, stabilizing the aircraft, and controlling its flight characteristics. These configuration files provide a starting point for configuring flight controller parameters, such as PID gains, sensor calibration, flight modes, and other settings specific to each flight controller which I used in my 3D printed drones.

## Supported Flight Controllers

At present, the repository supports configuration files for the following 3D Printed drone:

- Nano3LR1 (Happymodel X12 AIO)
- Nano3LRG (JHEMCU GSF405A-BMI)

## Usage

To use the configuration files provided in this repository, follow these steps:

1. Copy the entire contents of the config file.
2. Open the Betaflight Configurator and go to the CLI tab.
3. Paste the entire content into the console.
4. Write "save" and the flight controller will reboot. Now the flight controller should be configured.

Warning! Check the relevant settings such as frequency to see if they are legal in your country.
