# Pwnagotchi Wi-Fi Security Project

## Overview
This project involves configuring and deploying a Pwnagotchi device to capture Wi-Fi handshakes for ethical hacking and network security research. The Pwnagotchi is based on a Raspberry Pi and uses machine learning to maximize the number of Wi-Fi handshakes it can capture.

## Tools & Technologies
- **Raspberry Pi Zero W**
- **Pwnagotchi Firmware**
- **Kali Linux**
- **Wireshark** (for analyzing the captured data)
- **Python** (for scripting)

## Setup & Installation
1. **Install the Pwnagotchi firmware**: Follow the official instructions from the [Pwnagotchi GitHub repository](https://github.com/evilsocket/pwnagotchi).
2. **Configure the device**: Customize the `config.toml` file to enable specific Wi-Fi channels and power settings.
3. **Run the device**: Deploy the Pwnagotchi and allow it to capture Wi-Fi handshakes in various environments.

## Key Features
- **Automated Wi-Fi handshake capture**: The Pwnagotchi device uses AI to optimize the capture process.
- **Data Analysis**: Use Wireshark to analyze the captured handshakes and assess network vulnerabilities.
- **Custom Configuration**: Adjusted power settings and channel selection for optimal handshake capture.

## Lessons Learned
- **Wi-Fi Security**: Gained hands-on experience in assessing the vulnerabilities of Wi-Fi networks.
- **Machine Learning**: Learned how the Pwnagotchi uses reinforcement learning to improve handshake capture efficiency.
- **Networking Tools**: Deepened knowledge of networking tools like Wireshark and aircrack-ng.

## Next Steps
- **Expand scope**: Plan to explore advanced de-authentication attacks and WPA cracking using the captured handshakes.
- **Further automation**: Automate data analysis with Python for faster processing of large datasets.
