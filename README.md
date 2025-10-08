# Wireshark Analysis

A short protocol analysis using Wireshark on Kali Linux.

## Start capture

Open Wireshark on Kali Linux and select the `eth0` interface to begin capturing packets.  
<img width="1719" height="915" alt="Start capture on eth0" src="https://github.com/user-attachments/assets/b935f3eb-f309-4afc-a5a2-798bbb99d5c1" />

## Generate traffic

Visit a couple of sites (for example, ibm.com and kali.org) to generate traffic for the capture.  
<img width="1712" height="888" alt="Browsing to generate traffic" src="https://github.com/user-attachments/assets/2a5e2572-3b49-4c95-9664-6fa9d890f794" />

## Filter for DNS

Apply the display filter `dns` to show only DNS packets, which reveals destination IPs and protocol details for name resolution.  
<img width="1728" height="911" alt="DNS filter results" src="https://github.com/user-attachments/assets/005b50f0-9ce3-486e-be32-7c9dffa79494" />
