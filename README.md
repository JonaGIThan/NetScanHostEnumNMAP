# NetScanHostEnumNMAP

# Internal Network Scanning & Host Enumeration with Nmap

## Overview

This project demonstrates an internal network security assessment performed using Nmap in a controlled lab environment. The assessment focused on host discovery, service enumeration, operating system detection, TCP/UDP port analysis, and lightweight vulnerability scanning against a local `/24` subnet.

The objective was to identify active devices, analyze exposed services, evaluate network exposure, and assess potential security risks commonly reviewed during network security assessments.

## Tools Used

* Nmap 7.98
* Nmap Scripting Engine (NSE)

## Skills Demonstrated

* Network Reconnaissance
* Host Discovery & Enumeration
* TCP/UDP Port Scanning
* Service Enumeration
* OS Fingerprinting
* Vulnerability Assessment
* Network Security Analysis

## Key Findings

* Identified active hosts within the subnet
* Confirmed only expected management ports were exposed
* Detected firewall filtering on multiple ports
* Identified weak TLS configurations and anonymous DH cipher support
* Verified minimal UDP exposure consistent with normal router functionality

## Recommendations

* Disable weak TLS ciphers
* Restrict remote administration access
* Update router firmware regularly
* Disable unnecessary services such as UPnP if not required

## Disclaimer

This project was conducted in a controlled and authorized lab environment for educational purposes only.
