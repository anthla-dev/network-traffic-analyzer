# tshark-network-analysis

Packet-level network traffic analysis and inspection toolkit built using **tshark (Wireshark CLI)** for protocol debugging, traffic parsing, and security-focused network inspection.

---

## Overview

This repository extends practical usage of `tshark` for analyzing raw network traffic at the packet level. It focuses on extracting structured insights from packet captures (PCAP files) and live traffic for debugging and security analysis.

The goal of this project is to explore how low-level packet inspection can be used for:
- Network debugging
- Traffic characterization
- Security and anomaly detection
- Protocol analysis (TCP/IP behavior)

---

## Features

- Packet capture parsing using tshark CLI
- Protocol-level filtering (TCP, UDP, ICMP, HTTP, etc.)
- Extraction of key packet metadata:
  - Source / destination IPs
  - Ports
  - Protocol types
  - Packet timestamps
- Traffic flow reconstruction from PCAP files
- Support for filtering suspicious or anomalous traffic patterns
- Command-line based workflow for reproducible analysis

---

## Example Usage

### 1. List available interfaces
```bash
tshark -D
