# MacOS- Termianl
Bassic terminal commands for my Mac OS X

### This code enables System Preferences -> Security & Privacy -> Allow app downloaded from: Anywhere
\>>> `sudo spctl --master-disable`

### This command lets you edit the bash tag
\>>> `vi .bash_profile`  [[or any note editor, nano]]
\>>> `vi .bashrc` [[for the header]]

### This command lets you disbale iTunes media key
\>>> `launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist`

### Terminal Preference
**Welcome**
nano ~/.zshrc
\>>> echo "Welcome to terminal, "; ipconfig getifaddr en1; echo "Calendar : "; cal

**Prompt**
PROMPT='%F{red}%D{%L:%M:%S} [K] %F{0} '

### Basic Commands
\>>> `ctl z` (exit)  

\>>> `esc esc` (twice) will show all the avalible commands on terminal  

\>>> `man` (manual)  

\>>> `sudo` (super user do)  

\>>> `clear` or (⌘ + K)  

\>>> `cal` (calander)  
\>>> `whoami` (net work id)  
\>>> `ls` (list current director)  
\>>> `cd` (change directory)  

### Network
\>>> `ifconfig` (shows network data)  
\>>> `sudo ssh _hostname_@_ipaddress`  
\>>> `vnctigherserver` (launches VNC, for screen sharing)  
- AFP allows for file drop
- VNC allows for screen sharing

Note* If device is connected to network, router will know its IP address.
