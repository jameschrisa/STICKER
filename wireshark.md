# Wireshark

## Description
Wireshark is a free and open-source packet analyzer. It's used for network troubleshooting, analysis, software and communications protocol development, and education.

## How it's used in security matters
Wireshark allows you to see what's happening on your network at a microscopic level. It's used for detecting network anomalies, analyzing potential attacks, and understanding network protocols.

## Command syntax
While Wireshark is primarily used through its GUI, it comes with a command-line version called tshark. The basic syntax for tshark is:

```
tshark [options] ...
```

## Example
To capture packets on a specific interface:

```
tshark -i en0 -c 100
```

This command captures 100 packets on the en0 interface.
