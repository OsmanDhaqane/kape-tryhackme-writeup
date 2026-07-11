# KAPE TryHackMe Writeup

This repository contains my writeup for the TryHackMe **KAPE** room.

In this room, I used KAPE to collect and process Windows forensic artifacts from the lab machine. I first worked with the GUI version, then ran KAPE from the command line using **KapeTriage** and **!EZParser**.

After the collection finished, I reviewed the parsed output with **EZViewer** and checked the relevant artifacts for each question. This included registry data, USB device evidence, recent application activity, Windows search history, known networks, and Jump List data.

## What I learned

This room helped me understand that KAPE is mainly used to collect and process forensic artifacts quickly. The analysis still requires knowing which Windows artifact can answer each question.

## Tools used

- KAPE
- gkape
- EZViewer
- Registry Explorer
- Eric Zimmerman tools through !EZParser

## Writeup

The full PDF writeup is available here:

[kape-tryhackme-writeup.pdf](./kape-tryhackme-writeup.pdf)

## Disclaimer

This writeup was created for educational and portfolio purposes only. All testing was performed in the relevant lab environment.

© 2026 Osman Dhaqane. All rights reserved.
