# RedGhost
Linux post exploitation framework designed to assist red teams in persistence, reconnaissance, privilege escalation and leaving no trace. 
![RG](https://user-images.githubusercontent.com/44454186/61614561-8d09bf00-ac53-11e9-85f2-cd2337d9ded1.PNG)

- Payloads

Function to generate various encoded reverse shells in
netcat, bash, python, php, ruby, perl

- SudoInject

Function to inject sudo command with wrapper function to run a reverse root shell everytime "sudo" is run for privilege     escalataion

- lsInject 

Function to inject the "ls" command with a wrapper function to run payload everytime "ls" is run for persistence


- Crontab

Function to create cron job that downloads payload from remote server and runs payload every minute for persistence


- GetRoot

Function to try various methods to escalate privileges


- Clearlogs

Function to clear logs and make investigation with forensics difficult


- MassInfoGrab

Function to grab mass reconaissance/information on system

- CheckVM

Function to check if the system is a virtual machine


- MemoryExec

Function to execute remote bash script in memory


- BanIp

Function to BanIp using iptables


## Installation

one liner to install RedGhost:
```
wget https://raw.githubusercontent.com/d4rk007/RedGhost/master/redghost.sh; chmod +x redghost.sh; ./redghost.sh
```

One liner to install prerequisites and RedGhost:
```
wget https://raw.githubusercontent.com/d4rk007/RedGhost/master/redghost.sh; chmod +x redghost.sh; apt-get install dialog; apt-get install gcc; apt-get install iptables; ./redghost.sh
```

### Prerequisites

dialog, gcc, iptables
