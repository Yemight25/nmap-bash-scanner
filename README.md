# Automated Network Reconnaissance using Nmap and Bash

## Project Overview
This tool is a Bash script that helps beginners learn how to perform network scanning using Nmap. It automates ping scans, port scans, and OS detection, saving all results into a file.

## Features
- Accepts a target IP or domain
- Performs:
  - Ping scan
  - Full port scan
  - OS detection & service version detection
- Saves the output to `results/[target]_scan.txt`

## How to Use
1. Open your terminal and run:
   ```bash
   ./scan.sh
Enter the target IP or domain when asked (example: scanme.nmap.org)

Wait for the scan to complete

View your results in the results folder
