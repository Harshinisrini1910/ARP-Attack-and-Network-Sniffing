# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

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
## OUTPUT:
![Screenshot (34)](https://github.com/Vinothini1711/EX-No.4.2.-CUT-SECTION-OF-SOLIDS/assets/144300204/67c4af04-0ca9-44eb-8a64-f0fcf76b42f0)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
 dsniff:
![Screenshot 2024-04-27 162800](https://github.com/Vinothini1711/ARP-Attack-and-Network-Sniffing/assets/144300204/7f8627c6-d19b-408f-9139-ff49acb79ae3)
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![Screenshot 2024-04-27 163429](https://github.com/Vinothini1711/ARP-Attack-and-Network-Sniffing/assets/144300204/94620779-c233-423f-8747-68e733d5e29c)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2024-04-27 163506](https://github.com/Vinothini1711/ARP-Attack-and-Network-Sniffing/assets/144300204/9393c07e-aa5d-4a04-b45e-79476aaa3e34)
Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-04-27 163521](https://github.com/Vinothini1711/ARP-Attack-and-Network-Sniffing/assets/144300204/11cdcff7-4bed-4f48-b4dc-abd96e29d1ff)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
