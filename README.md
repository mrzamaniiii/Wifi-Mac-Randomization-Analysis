# Wi-Fi MAC Randomization Analysis

This repository contains a study on MAC address randomization behavior in Wi-Fi probe requests, using empirical data from two smartphones: an iPhone 14 Pro Max and a Samsung Galaxy A36.

## Overview

Modern smartphones increasingly use randomized MAC addresses to enhance user privacy during Wi-Fi network discovery. This project investigates how randomization varies across:

- Device manufacturers
- OS and hardware versions
- Operational conditions (Wi-Fi status, screen state, power-saving mode)

## Experiment Setup

- **Devices Tested:**
  - iPhone 14 Pro Max
  - Samsung Galaxy A36

- **Tooling:**
  - Wireshark (monitor mode)
  - ASUS laptop with Wi-Fi adapter supporting 802.11 capture

- **Conditions:**
  - 6 different combinations of Wi-Fi ON/OFF, screen ON/OFF, and power-saving ON/OFF
  - Each test lasted ~20 minutes, under controlled indoor conditions on Wi-Fi channel 2

## Files

- `*.pcap`: Raw Wi-Fi packet captures from various scenarios
- `WI_Report.Asal_Abbasnejad.Mohmmadreza_Zamani.pdf`: Full report describing methodology, results, and conclusions
