
# DrMAC - MAC Address Management Tool 🌐🛠️

DrMAC is a powerful and user-friendly tool designed for network administrators and tech enthusiasts. It allows you to manage and change MAC addresses of network interfaces on a Linux system easily. With DrMAC, you can quickly change your MAC address, reset it to its original value, and view detailed information about your network interfaces.

## Features 🌟

- 🔄 Easily change the MAC address of network interfaces.
- 🎯 Reset the MAC address to its original value.
- 🔍 View detailed information about network interfaces.
- 📝 Store original MAC addresses in a hidden file for easy recovery.
- 🛠️ User-friendly command-line interface.

## Installation 📦

You can download and run DrMAC as a Python script. Ensure you have Python installed on your system. Follow these simple steps:

1. Download the `DrMAC.py` script from the GitHub repository.
2. Give executable permissions to the script:

   ```bash
   chmod +x DrMAC.py
   ```

## Usage 🖥️

Run DrMAC from the command line using Python. Here are some common commands:

1. To change the MAC address:

   ```bash
   sudo python3 DrMAC.py -i interface_name -m new_mac_address
   ```

2. To reset the MAC address to its original value:

   ```bash
   sudo python3 DrMAC.py -i interface_name -r
   ```

3. To list all network interfaces:

   ```bash
   sudo python3 DrMAC.py -l
   ```

4. To show detailed information about a specific interface:

   ```bash
   sudo python3 DrMAC.py -i interface_name -d
   ```

## Contribution 👥

Your contributions are welcome! If you would like to improve DrMAC, feel free to fork the repository and submit your pull requests.

## License 📄

DrMAC is released under the MIT License. Check out the `LICENSE` file for more details.

---
**Note:** This tool is intended for educational and legal purposes only. The developers are not responsible for any misuse or damage caused by this tool.

**Note:** Ensure your actions comply with local laws and regulations. 🚨
