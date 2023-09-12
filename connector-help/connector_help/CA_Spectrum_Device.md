---
uid: Connector_help_CA_Spectrum_Device
---

# CA Spectrum Device

The **CA Spectrum Device** driver is used to display information and alarms for a device in the **CA Spectrum Infrastructure Manager**.

## About

The device info and alarms are retrieved using the **RESTful HTTP Web Service API** in CA Spectrum.

This driver is automatically generated by the driver **CA Spectrum**, range **2.0.0.x**.

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | 10.0                        |
| 2.0.0.x          | Unknown                     |

## Installation and configuration

### Creation

This driver is used by DVE child elements that are **automatically created** by the parent driver [CA Spectrum](xref:Connector_help_CA_Spectrum) from range 2.0.0.x onwards.

## Usage

### General

This page displays the **ID**, **Name**, **Type** and other general parameters related to the device.

### Alarms

This page displays all the alarms for the device in the **Alarms** table. The **Alarm Count** is also displayed at the top of the table and can be used for alarm monitoring purposes.