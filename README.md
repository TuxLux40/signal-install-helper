This is a little shell script for automated installations of the official signal linux client für debian based systems. It streamlines the installation and launch of Signal Desktop.

# This tool:
💫 installs *nala* for a pretty output  
🔑 Fetches and installs the official Signal GPG signing key and repository  
🛠️ Handles necessary dependencies of *ALSA* or *PipeWire* libraries (I needed to do this because it wouldn't launch in my distrobox container)  
🌈 Colorized, emoji-enhanced status messages  

# Usage  
    git clone https://github.com/TuxLux40/signal-install-helper.git  
    cd signal-install-helper  
    chmod +x install-signal.sh  
    sudo ./install-signal.sh  

# What's the point?  
I had problems (re-)installing Signal in Distrobox and got tired of manually copying and pasting, so I made this script to save time in the future.
