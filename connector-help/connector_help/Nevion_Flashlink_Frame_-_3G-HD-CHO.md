---
uid: Connector_help_Nevion_Flashlink_Frame_-_3G-HD-CHO
---

# Nevion Flashlink Frame - 3G-HD-CHO

This exported driver shows data from a 3G-HD-CHO module in a Nevion Flashlink frame.

## About

This is an **SNMP** driver that is automatically generated by the parent driver [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

### Ranges of the driver

| **Driver Range** | **Description**                                   | **DCF Integration** | **Cassandra Compliant** |
|------------------|---------------------------------------------------|---------------------|-------------------------|
| 1.0.0.x          | Basic range                                       | No                  | Yes                     |
| 2.0.0.x          | Tree controls added to monitor parameters.        | No                  | Yes                     |
| 2.0.1.x          | Audio Block status fix (ONLY for firmware 2.0.4). | No                  | Yes                     |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 2.0.1.x          | 5.0.4                       |

## Installation and configuration

### Creation

This driver is used by DVE child elements that are **automatically created** by the parent driver [Nevion Flashlink Frame](xref:Connector_help_Nevion_Flashlink_Frame).

## Usage

### General Page

This page displays general information about a 3G-HD-CHO module, including:

- Type
- Card Status
- Chassis Number
- Slot Number
- Label
- Alarm Status
- Alarm Trap
- Alarm Count
- Main Element Name

### Changeover

This page displays the **Changeover Table**, which contains information about cho1BlockTable parameters.

It also allows you to configure the **Mode**, **Current Input**, **Main**, **Backups, Rule**, **Latch**, **Hold** and **Lock Time** and **Alarms**.

### GPIO Page

This page displays the **General Purpose Input Output Table**, which contains information regarding I/O blocks.

It also allows you to configure the **Mode**, **Status**, **Description** and **Alarms**.

### Output Selector Page

This page displays the **Output Selector Table**, which contains information about output parameters.

### Reclocker Page

This page displays the **Reclocker Table**, which contains information about reclocker parameters.

It also allows you to view the Reclocker **Num**, **Status** and **Bit Rate**, as well as to configure **Config**, **ASI**, **Bandwidth** and **Alarms**.

### Signal Input Page

This page displays the **EQ Table**, which contains information about EQ parameters.

It also allows you to view the **Num** and **Status**, as well as to configure **Config** and **Alarms**.

### Signal Integrity Page

This page displays the **Monitor Table**, which contains information about monitor parameters.

It also allows you to configure **Monitor Alarm**, **Error Count**, **Error** **Delta** and **Error** **Free Alarm**, **FF-CRC**, **AP-CRC**, **LOCK**, **ANCS**, etc.

### Voltage Page

This page displays the **Voltage Table**, which contains information about voltage measurements.

It also allows you to configure the **Upper** and **Lower Limit** and **Alarms**, as well as to view the **Nominal** effect and the **Value** in Volts and Watts.