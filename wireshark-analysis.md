
---
layout: default

title: Mapping Network Traffic with Wireshark

---

# Mapping Network Traffic with Wireshark 🕵️‍♂️

**Project Date:** May 2026

In this project, I used Wireshark to capture and analyze live network traffic to understand how data moves across a local network.

## 1. Capture Objectives
* Identify active protocols (TCP, HTTP, DNS).
* Analyze the "Three-Way Handshake" for secure connections.
* Detect any unencrypted (Plaintext) traffic.

## 2. Analysis & Findings
Using Wireshark's display filters, I was able to isolate specific traffic patterns:
* **Filter Used:** `ip.addr == [Your IP]`
* **Observation:** Successfully identified the sequence of SYN, SYN-ACK, and ACK packets.

## 3. Security Insight
Analyzing traffic with Wireshark is essential for detecting "Man-in-the-Middle" (MITM) attacks and unauthorized data exfiltration.
