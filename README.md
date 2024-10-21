# Pwnagotchi Wi-Fi Security Project

## Overview
This project demonstrates the setup of a Pwnagotchi device using a **Raspberry Pi Zero W/H**. The Pwnagotchi is configured to capture Wi-Fi handshakes in a network for ethical hacking and security research. This project is based on the [Pwnagotchi GitHub repository by Jayofelony](https://github.com/jayofelony/pwnagotchi) and was built following [this video tutorial](https://www.youtube.com/watch?v=gyKT_mASSuc).

## Hardware Used
- **Raspberry Pi Zero W/H**
- **Micro SD Card (16GB or higher)**
- **Pwnagotchi Firmware**
- **USB Power Supply**
- **Wireshark** for handshake analysis

## Setup & Installation

1. **Flash the Pwnagotchi firmware** onto the SD card using **Balena Etcher**. You can download the firmware from the [official Pwnagotchi GitHub](https://github.com/evilsocket/pwnagotchi).
   
2. **Modify the `config.toml` file** with settings optimized for the Raspberry Pi Zero W/H, including channel hopping and power settings:
   - Set `main.plugins.ai.enabled = true` to enable the AI plugin for optimizing Wi-Fi handshake captures.
   
3. **Follow the detailed setup guide** from [Jayofelony’s GitHub repository](https://github.com/jayofelony/pwnagotchi) for Raspberry Pi-specific instructions.

4. **Run the Pwnagotchi**: Power up the Raspberry Pi and let the Pwnagotchi start capturing Wi-Fi handshakes.

5. **Analyze captured handshakes**: Use **Wireshark** or **aircrack-ng** to analyze the captured data and test network security.

## Key Features
- **Automated Wi-Fi handshake capture** using a Raspberry Pi Zero W/H.
- **AI-optimized capture process** with channel hopping and power adjustments.
- **Custom configuration**: `config.toml` file tailored to maximize efficiency in capturing handshakes.

## Tools & Technologies
- **Pwnagotchi firmware**
- **Raspberry Pi Zero W/H**
- **Wireshark** for packet capture analysis
- **Python** (for scripting and automation)

## Lessons Learned
- **Wi-Fi Security**: Practical experience in capturing and analyzing Wi-Fi handshakes for security testing.
- **Device Configuration**: Learned how to configure and optimize a Pwnagotchi on Raspberry Pi Zero W/H.
- **AI Optimization**: Explored how the AI feature in Pwnagotchi enhances capture efficiency.

## Next Steps
- **Implement WPA handshake cracking** using tools like **aircrack-ng**.
- **Explore de-authentication attacks** and their prevention methods.

## References
- [Pwnagotchi Official Repository](https://github.com/evilsocket/pwnagotchi)
- [Jayofelony's Pwnagotchi Guide](https://github.com/jayofelony/pwnagotchi)
- [YouTube Video Guide](https://www.youtube.com/watch?v=gyKT_mASSuc)
