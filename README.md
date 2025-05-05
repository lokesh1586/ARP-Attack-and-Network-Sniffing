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
![Screenshot 2025-05-05 102656](https://github.com/user-attachments/assets/cbb79df2-5382-4cf2-9556-36f1462d4237)

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![Screenshot 2025-05-05 110430](https://github.com/user-attachments/assets/9716a469-a2ed-41f5-ba0c-115861579d5d)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![Screenshot 2025-05-05 102637](https://github.com/user-attachments/assets/63f72ad0-34a3-40d1-8021-9aab9b167652)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2025-05-05 110540](https://github.com/user-attachments/assets/e687b974-1306-4304-be37-7d247004959d)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-05-02 153443](https://github.com/user-attachments/assets/b558db58-b203-4c8f-bb25-bb762b8893f5)


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
