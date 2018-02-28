# My Customization

The Customization I added to my USB is as follow:

* Setting a password on /root
* Setting a password on /home/ubuntu
* Setting /home/ubuntu to /home/KaoXiong

## Documentation

Setting a password for /root and /home/ubuntu was accomplished using the command in *7.3.4 Manipulating Users and Passwords*
from the book: *How Linux work - What Every Superuser Should Know*

The command are as follow:

~~~shell
passwd root
~~~

After typing in the command you will be ask to enter the new password and to retype the password as such:

~~~shell
Enter new UNIX password: 
Retype new UNIX password: 
~~~

and for /ubuntu

~~~shell
passwd ubuntu
~~~

I was able to change /ubuntu to /KaoXiong using command found on [https://askubuntu.com/questions/34074/how-do-i-change-my-username]
The command are as follow: 

~~~shell
sudo usermod -l newUsername oldUsername
~~~

I changed 'newUsername' to my desire name 'KaoXiong' and 'oldUsername' to 'ubuntu'



#### Thank You,
#### Kao Xiong
