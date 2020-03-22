# Configure E-mail server
<hr>

## Step1:DNS configuration

For E-mail configuration we have to configure our DNS that is to tell our DNS that mail.netcamp.in is our mail domain for this perform the following step.

**Step 1**: Browse the 192.168.1.100:10000

**Step 2**: Log in as root

**Step 3**: Now go to server --> Bind DNS server --> netcamp.in --> mail server.

**Step 4**: Fill the priority as well as E-mail domain carefully.

<img src="https://user-images.githubusercontent.com/52023930/77251890-f7598000-6c76-11ea-9259-f17584c5c260.png" width="700" height="300"/>

<br><br><br><br>
<hr>

## Step 2: Network configuration

Now, we have to inform our email server 192.168.1.100 that it has mail.netcamp.in and netcamp.in for this perform the following steps.

**Step 1**: Browse 192.168.1.200

**Step 2**: Log in a root

**Step 3**: Go to networking --> networking configuration --> host address

**Step 4**: Now here put mail.netcamp.in and netcamp.in

<img src="https://user-images.githubusercontent.com/52023930/77251940-68009c80-6c77-11ea-88cd-2ab8948634e2.png" width="700" height="300"/>

**Step 5**: Now simply click on save and apply changes.

<br><br><br><br>
<hr>


## Step 3: Apache configuration

For apache configuration of email server perform the following steps

**Step 1**: Browse  192.168.1.200

**Step 2**: Log in as root

**Step 3**: Go to servers --> apache server 

**Step 4**: Now put the specific address 192.168.1.200 and root folder as /usr/share/squirrelmail and domain as mail.netcamp.in

<img src="https://user-images.githubusercontent.com/52023930/77252028-c594e900-6c77-11ea-9038-51665184f1a4.png" width="700" height="300"/>

**step 5**: Now simply click on create now as shown in the above image and apply changes.

<br><br><br><br>
<hr>


## Step 4: SMTP Configuration

Now  we have to configure as it is the main port(port no. 25) which can transfer email as a files for send mail transfer protocol configuration perform the following steps

**Step 1**: Browse as 192.168.1.200

**Step 2**: Log in as root

**Step 3**: Now go to servers --> send mail configiuration --> send mail option.

<img src="https://user-images.githubusercontent.com/52023930/77252043-dcd3d680-6c77-11ea-8ac8-9e9f3ecf0150.png" width="700" height="300"/>

**Step 4**: Remove the address between port and name.

**Step 5**: Simply click on save and apply changes.

<br><br><br><br>
<hr>


## Step 5: IMAP AND POP3 Configuration

Now for email configuration we have to open the IMAP port (port no. 143) and pop3 port(port no. 110) to connect our users with the SMTP. To configure IMAP and POP3 perform the following steps

**Step 1**: Browse as 192.168.1.200

**Step 2**: Log in as root

**Step 3**: Go to servers --> IMAP and POP3 configuration --> networking and protocol

**Step 4**: Select the all the four ports in the below given image.

<img src="https://user-images.githubusercontent.com/52023930/77252128-494ed580-6c78-11ea-89d1-2a87af276f28.png" width="700" height="300"/>

Now simply save and apply changes.

<br><br><br><br>
<hr>


## Step 6: User configuration

This is the last step for email configuration as we simply add the users chairman, sales1, sales2, accounts1, accounts2 etc....

<img src="https://user-images.githubusercontent.com/52023930/77252203-831fdc00-6c78-11ea-8d70-4919bb093453.png" width="700" height="300"/>

and simply give the password to all the users.

<br>

<img src="https://user-images.githubusercontent.com/52023930/77252215-84510900-6c78-11ea-96d6-03afdba89fa9.png" width="700" height="300"/>

Now this is the show time we have configure our email server successfully. To test it we first login as chairman.

<br>

<img src="https://user-images.githubusercontent.com/52023930/77252266-bd897900-6c78-11ea-893f-99ddb74e6f3e.png" width="700" height="300"/>

and now we will update the personal information of the user.

<br>


<img src="https://user-images.githubusercontent.com/52023930/77252268-bebaa600-6c78-11ea-9826-3a9dd63dce65.png" width="700" height="300"/>

After this we will send the email to sales1 person.

<br>


<img src="https://user-images.githubusercontent.com/52023930/77252271-bfebd300-6c78-11ea-99ba-1a5c6b24ede4.png" width="700" height="300"/>

Now log in as sales1 and then check out its inbox.

<br>


<img src="https://user-images.githubusercontent.com/52023930/77252320-148f4e00-6c79-11ea-857f-18b72fee9a8a.png" width="700" height="300"/>

<br>


HURRAH!!!! We have successfully completed the mail server.
