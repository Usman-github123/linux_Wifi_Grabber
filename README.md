# Linux-Wifi-Grabber
This Script is used to search for Wi-Fi passphrases (PSKs) stored by NetworkManager on Linux systems. Specifically, it searches for Passwords within the NetworkManager connection profiles, which typically Displays the Wi-Fi password in plain text.

Usage:

    1. cd linux-Wifi-Grabber
    2. chmod +x main.py 
    3. python3 main.py
    
Important Notes:
    
    This command reveals Wi-Fi passwords, so use it with caution and ensure no unauthorized individuals can see the output.
    Not all Wi-Fi networks store passwords in this way, especially if the network uses a different authentication method, like enterprise WPA2.
    The command may not return any results if the stored passwords are encrypted or not saved in the connection profiles.

This command can be useful for retrieving forgotten Wi-Fi passwords or for troubleshooting network configurations on your system.
