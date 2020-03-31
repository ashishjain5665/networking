# Configure the folders and the users
<hr>
Now we have to made some users :

1.	Chairman - which can access every folder of individual department.

2.	Sales1, Sales2 - which can access sales department data folder for writting and driver folder for just read.

3.	Account1, Account2 -  which can access accounts department data folder for writting and driver folder for just read.

4.	Research1, Research2 -  which can access research department data folder for writting and driver folder for just read.

<b>Step 1</b>: we have firstly add some groups in our server.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984849-65b1d880-7330-11ea-8448-6b40592bf0a4.png" width=700 height=300 >
<br><br>

<b>Step 2</b>: Now we have to allocate each user to a particular group like sales1, sales2 to a compsale group.

Chairman will be in each group as it can access everything.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984853-677b9c00-7330-11ea-8706-5a5c62dde161.PNG" width=700 height=300 >
<br><br>

<b>Step 3</b>: Now we have to change the permission of sales, research, accounts folder to 750.
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984855-69455f80-7330-11ea-9005-c5ab6c55c7c2.PNG" width=700 height=300 >
<br><br>
<b>Step 4</b>: Now go to in the sales folder create two more folder data and drivers . Now change the group of the data folder with the compsale folder and change the permission to 777.

<b>Step 5</b>: Now change the permission of driver folder to 770 now change the group of driver folder with chairman .

<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984859-6a768c80-7330-11ea-9d92-519163fc7309.PNG" width=700 height=300 >
<br><br>

<b>Step 6</b>: Perform the Step 3, Step 4, Step 5, For research as well as account folder
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984861-6cd8e680-7330-11ea-82ca-c38f371dc762.PNG" width=700 height=300 >
<br><br>
<img src="https://user-images.githubusercontent.com/52023930/77984865-6ea2aa00-7330-11ea-9794-8241e6a23e17.PNG" width=700 height=300 >
