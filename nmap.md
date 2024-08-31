# Nmap

## Description
Nmap (Network Mapper) is a free, open-source tool used to discover hosts and services on a network, thus creating a "map" of the network.

## How it's used in security matters
Nmap is used for network inventory, managing service upgrade schedules, and monitoring host or service uptime. It can also be used to detect potential vulnerabilities in a network.

## Command syntax
The basic syntax for Nmap is:

```
nmap [Scan Type...] [Options] {target specification}
```

## Example
To perform a basic scan of a host:

```
nmap 192.168.1.1
```

This command performs a basic scan of the host at IP address 192.168.1.1, showing open ports and services.
