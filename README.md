# WebBlocker
This is real world program which blocks certain distracting website like Facebook, Youtube etc during your work hours.
1. Every system have host file whether it is Mac, Windows or Linux.
Host file in Mac and Linux :
/etc/hosts
Host file in Windows:

2. C:\Windows\System32\drivers\etc
Working of host file: Host is an operating system file which maps hostnames to IP addresses. In this program we will be mapping hostnames of websites to our localhost address. Using python file handling manipulation we will write the hostname in hosts.txt and remove the lines after your working hours.
