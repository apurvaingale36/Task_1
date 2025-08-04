# Task_1

# Network Reconnaissance Report

## Tools Used

* **Kali Linux**
* **Nmap**
* **Wireshark**

## Steps Performed

1. **Found Local IP Address**

   * Used Kali Linux terminal to identify the local IP address.

2. **Scanned Open Ports with Nmap**

   * Command used:

     ```
     nmap -sS <ip-address>
     ```
   * This performed a TCP SYN scan to discover open ports on the system.

3. **Open Ports Found**


     ```
     22/tcp - SSH  
     80/tcp - HTTP  
     443/tcp - HTTPS  
     ```


4. **Packet Capture with Wireshark**

   * Captured packets for traffic related to the scanned IP address.
   * Please refer to the attached screenshots (SS) for detailed packet analysis.

