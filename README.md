# Ex-No.4b-Execution-Of-NetworkCommends-Tracert

## AIM
Use of Network commands in Real Time environment
## Software 
Command Prompt And Network Protocol Analyzer
## Procedure 
To do this EXPERIMENT- follows these steps:

In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer
All commands related to Network configuration which includes how to switch to privilege mode
and normal mode and how to configure router interface and how to save this configuration to
flash memory or permanent memory.
This commands includes

• Configuring the Router commands

• General Commands to configure network

• Privileged Mode commands of a router

• Router Processes & Statistics

• IP Commands

• Other IP Commands e.g. show ip route etc.

## PROGRAM
```
from scapy.all import* 
target = ["www.google.com"] 
result, unans = traceroute(target,maxttl=32) 
print(result,unans) 
```
## OUTPUT

![image](https://github.com/user-attachments/assets/0743fcd9-19f3-4ef8-b31d-0bdd8dc96c5c)

## RESULT
Thus, the python program for simulating tracert command was successfully executed. 
