# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/abinayasangeetha/ARP-Attack-and-Network-Sniffing/assets/119393675/139cbb04-3c45-4f85-a375-fe969d2de43b)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/abinayasangeetha/ARP-Attack-and-Network-Sniffing/assets/119393675/3ec064cf-ef8e-40ab-a8ff-090f10225659)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/abinayasangeetha/ARP-Attack-and-Network-Sniffing/assets/119393675/90b6d617-6322-476e-90ad-e25fb43a600d)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/abinayasangeetha/ARP-Attack-and-Network-Sniffing/assets/119393675/6aff966e-c536-4cd2-a46f-eeee0f01fb20)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/abinayasangeetha/ARP-Attack-and-Network-Sniffing/assets/119393675/69e0ed19-049e-480a-be3e-d0e84c14230d)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
