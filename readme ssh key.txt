Creating an SSH private and public key
--------------------------------------

Open GIT Bash

Type: ssh-keygen -t rsa -C "<gmail address>"

passphrase: usual.password001

Authenticate the connection
---------------------------

Type: ssh -T git@github.com

Enter passphrase