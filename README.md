# Network Traffic Analyzer

Packet-level network traffic analysis tool built using **tshark (Wireshark CLI)** for protocol inspection, traffic parsing, and security-focused network debugging.

This project explores how low-level packet inspection can be used to understand, debug, and analyze real network behavior.

---

## Overview

The Network Traffic Analyzer processes packet capture (PCAP) files and live network traffic to extract structured insights from raw packets.

It focuses on:
- Protocol-level traffic inspection (TCP, UDP, ICMP, HTTP)
- Network flow reconstruction
- Traffic filtering and analysis
- Security-oriented packet pattern detection

---

## Features

- PCAP file parsing using tshark CLI
- Live network traffic capture support
- Protocol filtering (TCP / UDP / ICMP / HTTP)
- Packet metadata extraction:
  - Source IP
  - Destination IP
  - Ports
  - Protocol type
  - Timestamps
- Traffic flow analysis
- Filtering for suspicious or anomalous traffic patterns
- Reproducible CLI-based workflow

---

## Example Usage

### List available interfaces
```bash
tshark -D
