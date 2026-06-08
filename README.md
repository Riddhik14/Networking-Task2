# Networking-Task2
Networking Task 02: Network Devices & IP Addressing
Date: June 8, 2026
Intern: Riddhi Kshatriya

Objective
The purpose of this task is to learn about network devices, IP addressing, DNS, routers, and how data travels through a network.

Part A: Network Devices Research

1. Router
Purpose:
A router connects different networks and provides internet access to devices.
How it Works:
It checks the destination IP address of data packets and sends them through the correct path.
Real-World Usage:
Home Wi-Fi routers used to connect phones, laptops, and smart TVs to the internet.

2. Switch
Purpose:
A switch connects multiple devices within the same network.
How it Works:
It uses MAC addresses to send data only to the intended device.
Real-World Usage:
Used in offices, schools, and computer labs to connect many computers.

3. Hub
Purpose:
A hub connects multiple devices in a network.
How it Works:
It sends incoming data to all connected devices without checking the destination.
Real-World Usage:
Rarely used today but may be found in older networks or testing environments.

4. Access Point (AP)
Purpose:
Provides wireless connectivity to devices.
How it Works:
It connects to a wired network and broadcasts a Wi-Fi signal.
Real-World Usage:
Used in colleges, hotels, shopping malls, and offices.

5. Firewall
Purpose:
Protects the network from unauthorized access.
How it Works:
It monitors incoming and outgoing traffic and blocks suspicious connections.
Real-World Usage:
Windows Firewall on a PC or security firewalls used by companies.

6. Modem
Purpose:
Connects a home or office network to the Internet Service Provider (ISP).
How it Works:
It converts signals from the ISP into digital data that computers can understand.
Real-World Usage:
The internet box installed by broadband providers.


Part B: IP Address Classification

IP Address              | Category              | Explanation
192.168.1.10         | Private                  | Falls within the private range 192.168.0.0 – 192.168.255.255
10.0.0.5                  | Private                  | Falls within the private range 10.0.0.0 – 10.255.255.255
172.16.5.20           | Private                  | Falls within the private range 172.16.0.0 – 172.31.255.255
8.8.8.8                    | Public                    | Public DNS server provided by Google
1.1.1.1                    | Public                    | Public DNS server provided by Cloudflare
192.168.100.1       | Private                  | Part of the private 192.168.x.x range


Part C: Understanding Your Network

Network Information
<img width="976" height="945" alt="Screenshot 2026-06-08 111845" src="https://github.com/user-attachments/assets/708180fc-0056-4904-a4bd-9f740589b4d2" />

 
Answers
1. Which IP range does your device belong to?
My device belongs to the private IP address range assigned by the local network.

2. Is it Public or Private?
It is a Private IP address because it is used only inside a local network.

3. What role does your router play in your network?
The router acts as a gateway between my local network and the internet. It forwards data to the correct destination.

4. What would happen if the DNS server stopped working?
Websites would not open using domain names because their IP addresses could not be found. Internet access through direct IP addresses may still work.


Part D: Network Communication Flow
Diagram

Your Device
↓
Router
↓
DNS Server
↓
Google Server
↓
Response Back to Device

Explanation
Step 1:
The user enters www.google.com into the browser.
Step 2:
The device sends a request to the DNS server to find Google's IP address.
Step 3:
The DNS server returns the correct IP address.
Step 4:
The request travels through the router and ISP network to Google's server.
Step 5:
Google processes the request and sends the webpage data back.
Step 6:
The browser receives the data and displays the webpage.


Part E: Practical Command Exercise
Commands Used:
nslookup
<img width="576" height="227" alt="Screenshot 2026-06-08 112212" src="https://github.com/user-attachments/assets/e7f64945-7d93-4aac-9870-30d71e72bca9" />

 
ping
<img width="911" height="311" alt="Screenshot 2026-06-08 112240" src="https://github.com/user-attachments/assets/fc08b172-e782-474a-b80b-21cb43fa65b0" />

 

Answers
1. What IP address did DNS return for Google?
The DNS server returned one of Google's public IP addresses.

2. Was the ping successful?
Yes, the ping was successful if replies were received and packet loss was 0%.

3. Why is DNS important before communication begins?
DNS converts domain names into IP addresses so devices can locate and communicate with servers on the internet.

Conclusion
This task helped me understand network devices, IP addressing, DNS, routers, and how data travels between devices and servers. I also learned how to use networking commands to diagnose and analyze network connections.
