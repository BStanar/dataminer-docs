---
uid: Connector_help_Axon_ACP_DLA41
---

# Axon ACP DLA41

The **DLA41** is based on third-generation audio and loudness management technology by Linear Acoustic. It protects viewers from **loudness shifts and loss of surround sound** in a simple, cost-effective, modular and hot-swappable manner next to over 150 other Synapse modules.

## About

This driver can be automatically generated by the driver **Axon ACP Manager**.

There are different possibilities available for **alarm monitoring** and **trending**.

### Version Info

| **Range** | **Key Features**             | **Based on** | **System Impact** |
|-----------|------------------------------|--------------|-------------------|
| 1.0.0.x   | Initial version \[SLC Main\] | \-           | \-                |

### Product Info

| **Range** | **Supported Firmware** |
|-----------|------------------------|
| 1.0.0.x   | 2213                   |

### System Info

| **Range** | **DCF Integration** | **Cassandra Compliant** | **Linked Components** | **Exported Components** |
|-----------|---------------------|-------------------------|-----------------------|-------------------------|
| 1.0.0.x   | No                  | Yes                     | \-                    | \-                      |

## Configuration

### Connections

#### IP Connection - Unicast

This driver uses a serial connection and requires the following input during element creation:

SERIAL CONNECTION:

- Interface connection:

- **IP address/host**: The polling IP of the device.
  - **IP port:** The IP port of the device.
  - **Bus address**: The bus address of the device.

#### IP Connection - Broadcast

This driver uses a serial connection and requires the following input during element creation:

SERIAL CONNECTION:

- Interface connection:

- **IP address/host**: The polling IP of the device.
  - **IP port**: The IP port of the destination.
  - **Bus address**: Use the value "any" inside of it.

### Initialization

No extra configuration is needed.

### Redundancy

There is no redundancy defined.

## How to use

This element has the following data pages:

- **General**: Displays general information about the card: Card Name, Card Description, SW Revision, HW Revision, etc.
- **Status**: Displays the status of the inputs and channel gains.
- **I/O:** Allows you to configure the inputs and outputs of the card, as well as the GPI Control.
- **Audio 1/4**: Allows you to configure gain, phase and delay for channels 1-4.
- **Audio 5/8**: Allows you to configure gain, phase and delay for channels 5-8.
- **Add-On:** The drop-down boxes on this page allow you to fill the Quad speed audio bus with the appropriate outputs for slots 1-32.
- **Preset**
- **Mixer**
- **Metadata:** Displays the status of the metadata parameters.
- **Alarm Priority**: Displays the event messages of the card, i.e. special messages generated asynchronously on the card.

## Notes

This driver is best combined with the **Axon ACP Frame Manager** driver, but can be used as a standalone driver as well