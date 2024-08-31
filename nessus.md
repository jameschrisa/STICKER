# Nessus (OpenVAS)

## Description
Nessus is a proprietary vulnerability scanning tool, but it has an open-source alternative called OpenVAS (Open Vulnerability Assessment System).

## How it's used in security matters
OpenVAS is used for identifying vulnerabilities in networks, systems, and applications. It helps security professionals and system administrators detect potential security weaknesses before they can be exploited by attackers.

## Command syntax
The basic syntax for running an OpenVAS scan is:

```
openvas-cli scan <target>
```

## Example
To scan a local network for vulnerabilities:

```
openvas-cli scan 192.168.1.0/24
```

This command initiates a vulnerability scan on the entire 192.168.1.0/24 subnet.
