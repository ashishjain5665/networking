# Configure DNS 
## DNS configuration

### Networking 
- Networking is a practice of linking of two or more computing devices with the pc, printers, faxes, etc... with each other connection between two devices is through physical media or logical media to share infromation, data and resources. Networks are  made with hardware and software.

### DNS 
- The Domain Name Systems (DNS) is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources. Each device connected to the Internet has a unique IP address which other machines use to find the device. DNS servers eliminate the need for humans to memorize IP addresses such as 192.168.1.1 (in IPv4), or more complex newer alphanumeric IP addresses such as 2400:cb00:2048:1::c629:d7a2 (in IPv6).

***

For our project we made a DNS server with the IP 192.168.1.100 as our DNS(Domain name server) 

<img src="https://user-images.githubusercontent.com/52023930/77153668-30032900-6ac0-11ea-93e6-fae6553ab3b8.jpg" width=700 height=400 >

Now we have to configure our DNS so we open GUI port (port no. 10000) now we have ,First of all we create a name server by following steps:

**Step 1**: First open 192.168.1.100:10000 

**Step 2**: Login as root.

**Step 3**: Click on servers, then go on bind DNS server and then click on create master zone and click addresses.

**Step 4**: Now create six domain names as 

⦁	mail.netcamp.in

⦁	www.netcamp.in

⦁	netcamp.in

⦁	research.netcamp.in

⦁	accounts.netcamp.in

⦁	sales.netcamp.in
 
****Now start the DNS server .****

<img src="https://user-images.githubusercontent.com/52023930/77154094-04347300-6ac1-11ea-9a4b-5241607b6932.png" width=700 height=400>

				
