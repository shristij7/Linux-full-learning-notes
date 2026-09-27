## **SSH**

SSH(Secure Shell) is a network communication protocol for connecting to a remote computer securely. Communication is done in an encrypted format. 



The default port for SSH client connections is 22. (Can be changed)



##### Syntax: 

ssh username@IP / ssh username@hostname



##### Commonly used for:

Remote command-line access

File transfers

Tunneling traffic

Server maintenance 

Application deployment 

Troubleshooting



##### Using SSH:

To use SSH, ssh server must be installed on the Linux server.

We can check using:

* rpm -qa | grep ssh or 
* check the file: file /etc/ssh/sshd\_config



**To install:**

install openssh-clients openssh-server



**To check IP:** ifconfig





