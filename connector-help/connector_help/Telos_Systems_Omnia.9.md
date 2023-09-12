---
uid: Connector_help_Telos_Systems_Omnia.9
---

# Telos Systems Omnia.9

This standard configuration offers processing for FM or AM, with optional and simultaneous processing for HD-1, HD-2 and HD-3. Each HD source can also be independently processed and encoded for stream audio. FM and AM transmitters can be processed simultaneously, if the FM and AM stations are 100% simulcast and from the same transmitter site.

## About

This driver monitors general status parameters of the device and input status parameters of 4 inputs.

**SNMP** is used to retrieve the device information. SNMP traps can be retrieved when this is enabled on the device.

In driver range 1.0.1.1, an additional **HTTP** connection is used to read and write device information.

### Ranges of the driver

| **Driver Range** | **Description**       |
|------------------|-----------------------|
| 1.0.0.1          | Initial version       |
| 1.0.1.1          | Added HTTP connection |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.1          | Unknown                     |
| 1.0.1.1          | 3.19.51                     |

## Installation and configuration

### Creation

#### SNMP connection

This driver uses a Simple Network Management Protocol (SNMP) connection and requires the following input during element creation:

SNMP CONNECTION:

- **IP address/host**: The polling IP of the device.
- **Device address**: Not required.

SNMP Settings:

- **Port number**: The port of the connected device, by default *161*.
- **Get community string**: The community string used when reading values from the device, i.e. *public*.
- **Set community string**: The community string used when setting values on the device, i.e. *private*.

#### HTTP Connection \[driver range 1.0.1.1\]

This driver uses a secondary HTTP connection and requires the following input during element creation:

HTTP CONNECTION:

- **IP address/host**: The polling IP of the device.

TCP/IP Settings:

- **IP port:** The port of the connected device, by default *7380*.
- **Bus address**: By default *bypassproxy*.

## Usage

### Status

This page contains **input status** parameters.

### Preset

This page contains **preset** parameters (**Input**, **FM**, **HD**, **Stream**, **Studio**).

### RDS \[Driver Range 1.0.1.1\]

This page contains **Radio Data System (RDS)** parameters (e.g. UECP, Radiotext).

### FM Options \[Driver Range 1.0.1.1\]

This page contains parameters for **FM Options**.

### Web Interface \[Driver Range 1.0.1.1\]

This page provides access to the web interface of the device. The web interface is only accessible when the client machine has network access to the product.