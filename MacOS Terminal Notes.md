# MacOS- Termianl
Bassic terminal commands for my Mac OS X

### This code enables System Preferences -> Security & Privacy -> Allow app downloaded from: Anywhere
\>>> `sudo spctl --master-disable`

### This command lets you edit the bash tag
\>>> `vi .bash_profile`  [[or any note editor, nano]]
\>>> `vi .bashrc` [[for the header]]

### This command lets you disbale iTunes media key
\>>> `launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist`

(vi is a text editor, like nano)
(I like export PS1="\t [K]") this will show the time (\t) and K prompt
OR
export PS1='\[\e[1;36m\] >> \[\e[m\] ' [[color coded]]

echo "Welcome to terminal, "; ifconfig | grep "inet " | grep -v 127.0.0.1 | cut -d\  -f2
echo "Today is $(date)"
echo ""
echo "Calendar : "
cal


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
