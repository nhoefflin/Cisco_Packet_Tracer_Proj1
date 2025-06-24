1. One router and one switch to be used 

2. 3 departments (Admin/IT, Finance/HR, Customer service/reception

3. Each department must be in different VLANs

4. Each department must have a wireless network for the users

5. Host devices in the network are required to obtain IPv4 address automatically

6. Devices in all the departments are required to communicate automatically  
  
  
  
  







Base Network of 192.168.1.0

Subnets = 3 

2^n = 3

n = 2 (borrowing two bits)

.11000000

2^6 + 2^7 = 192

Mask: 255.255.255.192

Block Size = 64


192.168.1.0/26
255.255.255.192/26


Subnet 1

Network ID:192.168.1.0

Broadcast ID:192.168.1.63

Usable IPs:192.168.1.1 - 192.168.1.62


Subnet 2 

Network ID:192.168.1.64

Broadcast ID:192.168.1.127

Usable IPs:192.168.1.65 - 192.168.1.126


Subnet 3 

Network ID:192.168.1.128

Broadcast ID:192.168.1.191

Usable IPs: 192.168.1.129 - 192.168.1.190
