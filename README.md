# Nmap Network Scan on macOS

## Overview
This project demonstrates how to use **Nmap** on macOS to perform a basic network scan to discover active devices and open ports in a local network.

## Steps Performed
1. Installed Nmap on macOS.
2. Identified local IP address using `ipconfig getifaddr en0`.
3. Determined local IP range (`192.168.29.0/24`).
4. Ran an Nmap TCP SYN scan using:
sudo nmap -sS 192.168.29.0/24
5. Saved the scan results to `scan_results.txt`.
6. Identified IP addresses and noted open or filtered ports.
7. (Optional) Plan to analyze packets using Wireshark.
8. Researched potential risks based on discovered open ports.

## File Details
- `scan_results.txt` — Contains the output of the Nmap scan.
- `README.md` — Describes the purpose and procedure of the project.

## Note
Running Nmap with `-sS` requires root privileges (`sudo`). Make sure you're connected to a valid network while scanning.

---

> This was part of a basic network reconnaissance and security auditing practice.
