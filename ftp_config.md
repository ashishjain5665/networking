# Configure File transfer protocol
<hr>
For file transfer protocol we have to open the port number 23 . for transfering the file between server and client machine. 

We have to check that FTP is open in our linux or not, for this we have to type command **"nmap"** in linux.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77536984-53184900-6ec3-11ea-93c4-352318758419.png" width=700px height=300px />
<br><br>
from this image we can clearly see that FTP port is not open to open the ftp port we have to type commad -  <b>"service vsftpd start"</b> .
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77536986-54497600-6ec3-11ea-957d-9a89e7af6d82.png" width=700px height=300px />
<br><br>
Now we can simply transfer bnetween our server and client machine for this we have used a software <b>Filezilla</b> which is simple in use and based on drag and drop method.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77536988-557aa300-6ec3-11ea-80cc-2e402b93115e.png" width=700px height=300px />
<br><br>
In this image we transfered a file named as <b>company.csv</b> from our client machine to the server.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77537089-80fd8d80-6ec3-11ea-9755-95aef2cb349e.png" width=700px height=300px />
<br><br>
<b>HURRAH!!!! The FTP is ready.</b>
