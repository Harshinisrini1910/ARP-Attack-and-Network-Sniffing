# EX : 4 Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
### OUTPUT:
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/e77ded8e-abbb-4875-8549-70f113664591)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/f1f7b4f6-4d6b-4270-ba08-a3db69dfc580)

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/f932e004-8d92-445e-95a5-b19e8280359c)


In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/fc3728ee-0e95-41d6-a644-eca870b6dbad)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/f5cd7fd0-4e08-4aae-8256-8cf635fec554)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
