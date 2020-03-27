# Configuration of DHCP

For dynamic post configuration protocol which can automatically give IP from a particular range to a client machine from IP pool. For this perform the following steps.

**Steps 1**: Browse as 192.168.1.200

**Step 2**: Log in as root.

**Step 3**: Now go to servers --> DHCP server --> add a new subnet 

**Step 4**: Now fill the details carefully shown in below image.

<img src="https://user-images.githubusercontent.com/52023930/77779210-2d807080-7078-11ea-98a3-23d32aa33943.png" width=700 height=300 />
<br><br>

<b>Step 5</b>: Now we have to give the gateway by clicking on edit client option.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77779215-2eb19d80-7078-11ea-8caa-1b3c007c0d92.png" width=700 height=300 />
<br><br>

Now start the server, we will face an error.

<img src="https://user-images.githubusercontent.com/52023930/77779216-307b6100-7078-11ea-907c-57019242c829.png" width=700 height=300 />
<br><br>

 To solve this error we have to rewrite a file which is in /etc/dhcpd.conf.
Add a line <b>"ddns-update-style ad-hoc;"</b>.

<img src="https://user-images.githubusercontent.com/52023930/77779291-51dc4d00-7078-11ea-874b-80d4d7eca7b0.png" width=700 height=300 />
<br><br>

Now again start the server.

HURRAHH!!!!! The DHCP is ready, we can test it by giving IP to our windows.

This image shows the IP before starting the DHCP server 

<img src="https://user-images.githubusercontent.com/52023930/77779303-530d7a00-7078-11ea-966f-428a32ffe1be.png" width=700 height=300 />
<br><br>

This image shows the IP after starting the DHCP server.

<img src="https://user-images.githubusercontent.com/52023930/77779309-543ea700-7078-11ea-9d96-462d2fd7290e.png" width=700 height=300 />
<br><br>

<b>DHCP COMPLETE </b>
