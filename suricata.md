# Suricata

## Description
Suricata is a high performance, open-source network IDS, IPS, and network security monitoring engine.

## How it's used in security matters
Suricata is used to monitor network traffic in real-time, detecting and preventing a wide range of threats including intrusion attempts, malware infections, and other malicious activities. It can be used as both an Intrusion Detection System (IDS) and an Intrusion Prevention System (IPS).

## Command syntax
The basic syntax for running Suricata is:

```
suricata [options] [runmode]
```

## Example
To run Suricata in IDS mode with a specific configuration file:

```
suricata -c /etc/suricata/suricata.yaml -i eth0
```

This command starts Suricata using the specified configuration file and monitors traffic on the eth0 interface.
