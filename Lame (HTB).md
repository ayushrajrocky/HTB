Here we starts Scanning Via Nmap

![Screenshot from 2022-03-04 12-11-32.png](https://github.com/ayushrajrocky/HTB/raw/main/a4b14a2180354602aaeb584352b50166.png)

here @port 21 FTP is Open and the version of the ftp server running there is vsftpd 2.3.4

There is a smb running

![Screenshot from 2022-03-04 12-11-32.png](https://github.com/ayushrajrocky/HTB/raw/main/af091f3760334f81be71f2cba635c7b4.png)

and there is a exploit available and also in msfconsole

![Screenshot from 2022-03-04 12-12-40.png](../_resources/Screenshot from 2022-03-04 12-12-40.png)

## Updatedb

![Screenshot from 2022-03-04 12-14-59.png](../_resources/Screenshot from 2022-03-04 12-14-59.png)

## Now we will perform post exploitation 

by creating a shadow and password file where we store data of /etc/shadow and /etc/passwd respectively 

and then 

unshadow passwd shadow

then we have to crack the hash to get the password
