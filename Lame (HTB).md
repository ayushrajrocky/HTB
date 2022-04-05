Here we starts Scanning Via Nmap

<img src="../_resources/Screenshot from 2022-03-04 11-59-19.png" alt="Screenshot from 2022-03-04 11-59-19.png" width="815" height="511">

here @port 21 FTP is Open and the version of the ftp server running there is vsftpd 2.3.4

There is a smb running

![Screenshot from 2022-03-04 12-11-32.png](../_resources/Screenshot from 2022-03-04 12-11-32.png)

and there is a exploit available and also in msfconsole

![Screenshot from 2022-03-04 12-12-40.png](../_resources/Screenshot from 2022-03-04 12-12-40.png)

## Updatedb

![Screenshot from 2022-03-04 12-14-59.png](../_resources/Screenshot from 2022-03-04 12-14-59.png)

## Now we will perform post exploitation 

by creating a shadow and password file where we store data of /etc/shadow and /etc/passwd respectively 

and then 

unshadow passwd shadow

then we have to crack the hash to get the password