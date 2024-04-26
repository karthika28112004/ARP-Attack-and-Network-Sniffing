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
![image](https://github.com/karthika28112004/ARP-Attack-and-Network-Sniffing/assets/128035087/08a1d169-5e07-4812-b162-bee9ad2fec5d)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/karthika28112004/ARP-Attack-and-Network-Sniffing/assets/128035087/375de303-7adc-4cc1-b9fb-3f0f074bad8d)


# dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/karthika28112004/ARP-Attack-and-Network-Sniffing/assets/128035087/47ae785b-a058-435f-94aa-b6d610b3e29a)

In Kali issue the following commands:sudo dsnifff
## OUTPUT:
![image](https://github.com/karthika28112004/ARP-Attack-and-Network-Sniffing/assets/128035087/38e18945-ad01-4cd4-8943-01fa367b0587)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
