
---
layout: default

title: Analyzing Brute Force Patterns

---

# Analysis of SSH Brute Force Attacks
**By: [Neha Lamba]

In this report, I explore how we can use Python to identify automated login attempts in server logs.

## 1. The Dataset
The data consists of 10,000 auth log entries. Using **Pandas**, I filtered for "Failed password" events.

## 2. Methodology
I used a simple Python script to group these failed attempts by IP address to find the most frequent attackers.

## 3. Findings
* **Total Attacks:** 452
* **Unique IPs:** 12
* **Most Targeted User:** 'root'

## 4. Conclusion
By analyzing this data, we can create a "Blocklist" to automatically update firewall rules.
![Security Terminal Analysis](terminal-screen.png)
