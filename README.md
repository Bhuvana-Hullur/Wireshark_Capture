# Wireshark HTTP Traffic Capture

## Overview

This task demonstrates capturing HTTP traffic using Wireshark on Kali Linux.

## Tools Used
- Wireshark (Kali Linux)
- Network Interface: eth0
- Website: http://example.com

## Capture Process
1. Started Wireshark with sudo wireshark.
2. Selected interface eth0 and began capture.
3. Visited an HTTP-based website using Firefox.
4. Applied the filter http to isolate relevant packets.
5. Saved the capture as wireshark_capture.pcap.

## File Included
- wireshark_capture.pcap: Packet capture containing HTTP requests and responses.

## Observations
Captured HTTP packets show GET requests and server responses, useful for learning how client-server communication works over the web.

