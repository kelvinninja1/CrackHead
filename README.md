# CrackHead
Easy, Simple Aircrack-Suite Replay Attacks
In lamence terms...
This enables any Kali Linux user to easily pull off a Wireless "Replay Attack" (steal router's password) with nothing more than the ability to copy/paste a BSSID, and to possess a ARP Injection Capable external wireless card
This has been tested against a WPA2-PSK router with CCMP enabled.

Full list of compatible cheap-O wireless cards here: http://www.codegeek.io/home/kali-linux-compatible-wireless-adapters/

Tested with a TP-Link TL-WN722N, which is like $13 from Amazon. 
https://www.amazon.com/Tp-Link-TL-WN722N-IEEE-802-11n-draft/dp/9800359850

# How to Install
Step 1. Unzip contents
Step 2. Navigate to the directory in terminal
"cd /$PATH/Folder that CrackHead Unzipped to"
Step 3. Chmod the setup.sh script
"chmod 777 setup.sh"
Step 4. Run the script
"./setup.sh"

Enjoy your crack pipe! And find a good wordlist to run the wireless hashes against.

# Dependencies
As always for all of my GitHub releases. You still require Python 2.7.13, Python-Pip, and Termcolor for Python Modules.
Run dependencyInstall.sh with the same steps if you do not have Termcolor (the error will show up telling you so).

# Other Points
Unlike the Wi-Fi Attack Autoloader Project, because Aircrack doesn't require any "funny business" or "hacking around" for your network settings, you should be able to use CrackHead without any significant changes to your Linux network settings.
