# Installing and Using OpenVPN with TryHackMe

This guide will walk you through the steps to install and configure OpenVPN on a Linux system to connect to TryHackMe. Follow the instructions below to complete the setup.

## Prerequisites
- A Linux system (e.g., Ubuntu, Debian, Kali Linux).
- Administrative privileges on the system.
- A TryHackMe account.

## Steps

### Step 1: Download OpenVPN Configuration File from TryHackMe
1. Go to [TryHackMe](https://tryhackme.com/) and log in to your account.
2. Navigate to the "Access" section in the dashboard.
3. Download the OpenVPN configuration file (`.ovpn`) for your connection.

![Download OpenVPN Config](https://i.imgur.com/VCPoCjB.png)

### Step 2: Install OpenVPN
Install OpenVPN using your package manager. For Debian-based systems like Ubuntu and Kali Linux, use the following command:
![Download OpenVPN Config](https://i.imgur.com/7wsUMyp.png)

### Step 3: Start OpenVPN
Go to Download folder and run the following command to start vpn 
sudo openvpn insertvpnfilename.vpn
![Download OpenVPN Config](https://i.imgur.com/BerhqBv.png)

### Step 4: Ensure VPN is running
Run the following command below 
ip a 
If VPN is running you should see a new ip address stable-privacy

Congrats you now have access to OpenVPN that is used to work on labs on TryHackme
