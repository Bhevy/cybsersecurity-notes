## Day 2 - Networking & OSI Model
### TCP vs UDP
- TCP (Transmission Control Protocol) is reliable and ensures data is delivered correctly.
- UDP (User Datagram Protocol) is faster but does not guarantee delivery.

### Ports
- Ports are like doors on a computer that allow different services to communicate
- Examples:
   - Port 80: HTTP (web)
   - Port 443: HTTPS (secure web)

 ### Subnetting
 - Subnetting is the process of dividing a large network into smaller networks.
 - It improves organisation, performance, and security.

### ARP (Address Resolution Protocol)
- ARP is used to find the MAC address of a device using its IP address on a local network.

### DHCP (Dynamic Host Configuration Protocol)
- DHCP automatically assigns an IP address and other settings (gateway, DNS) to a device.

### OSI Model (7 Layers)
1. Application - where the user interacts with the network (browser, apps)
2. Presentation - formats and secures the data; Encryption and data formatting (HTTP, HTTPS)
3. Session - manages the connection between the devices (staying logged into a website)
4. Transport - controls how the data is sent; ensures the delivery (TCP & UDP)
5. Network - handles IP addresses and routing (IP addresses)
6. Data link - Handles communication between devices on the same network (uses MAC addresses)
7. Physical - actual transmission of data (electrical signals, cables, WIFI)

### LINUX PRACTICE
Created folders using 'mkdir'
Navigated usinf 'cd'
Created files using 'touch'
Deleted files using 'rm'
Deleted folders using 'rm -r'
Rename files using 'mv'

### What I learnt today
- How devices communicate using IP and ports
- Difference between TCP and UDP
- Basic networking protocols (ARP, DHCP)
- OSI model and how data flows through layers
- File handling in Linux

### Challenges faced
- Understanding the OSI layers
