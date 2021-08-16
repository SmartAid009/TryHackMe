# TryHackMe
#This writeup is only who just wants hint!Thank You!
#First starts with nmap 
We found there is website running of port 80
Nmap default script also shows us robots.txt
Which shows as /fuel directory
Exploring we found its fuel CMS 
Then i tried loging in with default credentials
It successfully gave me admin portal 
I tried uploading reverse shell but it doesnot allow me to do it.
then i searched for exploit which gave me remote code execution exploit
I simply tried with then it gave me a reverse shell
For root i tried searching for some  database files
I found database.php inside config directory of /var/www/html/fuel ......
It gave me a root password
I simply logged in as root and got root flag.
