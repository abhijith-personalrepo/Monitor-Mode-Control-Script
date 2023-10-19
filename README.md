# Monitor Mode Control Script

This is a simple Bash script for controlling monitor mode on a wireless network interface. Monitor mode is a special mode that allows you to capture network traffic, making it useful for various network analysis and security tasks.

## Prerequisites

Before you can use this script, you need to ensure that you have the `aircrack-ng` suite installed, which includes the `airmon-ng` tool. If it's not installed, the script will prompt you to install it.

### Installing aircrack-ng

If `aircrack-ng` is not installed on your system, the script will ask you if you want to install it. If you choose to install it, the script will run the following commands:

```bash
sudo apt-get update
sudo apt-get install aircrack-ng
```

## Usage

1. **Enable Monitor Mode:** To enable monitor mode on a wireless interface, run the script and select option 1. You will be prompted to enter the name of the wireless interface you want to enable monitor mode for.

2. **Disable Monitor Mode:** To disable monitor mode on a wireless interface, run the script and select option 2. You will be prompted to enter the name of the wireless interface that is currently in monitor mode.

3. **Quit:** To exit the script, select option 3.

## How to Run the Script

You can run the script by executing it in your terminal. Make sure it has execute permissions. You can grant execute permissions using the following command:

```bash
chmod +x mon
```

Then, run the script with:

```bash
./mon
```

## Note

- Ensure that you have the necessary permissions to execute the script, and it's advisable to run it as a superuser or using `sudo` to manage network interfaces effectively.

- This script is intended for educational and legitimate network administration purposes. Please use it responsibly and in compliance with applicable laws and regulations.

- The script is designed for Linux systems using the `apt` package manager. If you are using a different package manager, you may need to modify the installation step accordingly.

Enjoy using the Monitor Mode Control Script for your network analysis and security tasks!
