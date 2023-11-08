# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

### STEPS:

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

![output 1](https://github.com/madhan0809/ARP-Attack-and-Network-Sniffing/assets/119165530/81f27200-1355-4e43-bc92-5b18edda4b2f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![output 2](https://github.com/madhan0809/ARP-Attack-and-Network-Sniffing/assets/119165530/d017d57b-4081-47d2-9cd6-fa16a47c1dc6)

### dsniff:






#### In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![output 3](https://github.com/madhan0809/ARP-Attack-and-Network-Sniffing/assets/119165530/8e878f75-4a9c-44dd-a87c-13d86920266f)

### In Kali issue the following commands: sudo dsnifff
## OUTPUT:

![output 4](https://github.com/madhan0809/ARP-Attack-and-Network-Sniffing/assets/119165530/fc749e56-22d5-4141-804a-0349e8926c14)


### Invoke the wireshark and examine the various menus  and controls of the tool:

![output 5](https://github.com/madhan0809/ARP-Attack-and-Network-Sniffing/assets/119165530/6fb6c66e-31d9-4526-9bd0-6440eef6d7b7)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
