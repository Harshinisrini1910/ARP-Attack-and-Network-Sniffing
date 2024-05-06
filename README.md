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
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/34e5b559-88fb-4da7-8eaf-a64ec0697811)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/40cdbfb9-f8b1-43b2-ae18-3108e26eef16)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/1b6807b7-5ce8-4553-9793-c0b061d91fc1)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/d09a45de-7403-45c7-8507-846e8b772412)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/161415847/bb3e7166-04a8-437d-8407-a67a91892999)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
