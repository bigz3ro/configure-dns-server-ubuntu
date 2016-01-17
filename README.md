# Fix: Error DNS error on Browser in Linux
Ubuntu Linux Configure DNS Name resolution

Type the following command, enter:
$ sudo vi /etc/resolv.conf

Or use nano text editor:
$ sudo nano /etc/resolv.conf

Append your ISP name server or free fast dns nameservers IP address as follows:
nameserver 208.67.222.222
nameserver 208.67.220.220
nameserver 202.51.5.52

Save and close the file. Test your dns configuration by typing the following commands:
$ host yahoo.com
$ nslookup google.com
$ ping nixcraft.in
