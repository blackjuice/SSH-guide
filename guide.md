# SSH

## Fast links

* [openSSL](https://www.openssl.org/source/): https://www.openssl.org/source/openssl-1.0.1j.tar.gz

* [zlib](http://www.zlib.net/): http://zlib.net/zlib-1.2.8.tar.gz

* [Getting started with SSH - Kimmo Suominen](https://kimmo.suominen.com/docs/ssh/)

## Links used

Generating SSH keys: https://help.github.com/articles/generating-ssh-keys/

INSTALANDO E CONFIGURANDO SERVIDOR SSH (UBUNTU): http://www.vivaolinux.com.br/dica/Instalando-e-configurando-servidor-SSH-%28Ubuntu%29

OpenSSL missing during ./configure. How to fix? http://superuser.com/questions/371901/openssl-missing-during-configure-how-to-fix

status report (personal github): https://github.com/blackjuice/SSH-guide/blob/master/guide.md

Working with SSH key passphrases: https://help.github.com/articles/working-with-ssh-key-passphrases/

SSH keys on ArchLinux: https://wiki.archlinux.org/index.php/SSH_Keys


## Installing PuTTY

How To Install & use Putty in Ubuntu Linux: http://www.linuxtechi.com/install-putty-in-ubuntu/

## Previous issues

### permission denied

http://serverfault.com/questions/381967/ssh-login-using-public-key-failed

http://www.linuxquestions.org/questions/ubuntu-63/how-to-ssh-into-localhost-permission-denied-publickey-4175455078/

http://askubuntu.com/questions/394305/public-key-authentication-failed

http://ubuntuforums.org/showthread.php?t=1355416

http://stackoverflow.com/questions/22530886/ssh-copy-id-no-identities-found-error

### ssh-keygen

https://help.github.com/articles/generating-ssh-keys/

http://superuser.com/questions/371901/openssl-missing-during-configure-how-to-fix

https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2

https://github.com/blackjuice/SSH-guide/blob/master/guide.md

https://help.github.com/articles/working-with-ssh-key-passphrases/

https://bbs.archlinux.org/viewtopic.php?id=160388

https://wiki.archlinux.org/index.php/SSH_Keys


## report

#### ssh access denied:

$ ssh limbo@192.168.1.47

The authenticity of host '192.168.1.47 (192.168.1.47)' can't be established.

ECDSA key fingerprint is ed:af:88:92:a3:09:e4:7e:2c:2b:08:75:62:61:ec:e7.

Are you sure you want to continue connecting (yes/no)? yes

Failed to add the host to the list of known hosts (/home/commander/.ssh/known_hosts).

limbo@192.168.1.47's password: 

Permission denied, please try again.

#### no identities

commander@ubuntu:~$ ssh-copy-id limbo@192.168.1.47

/usr/bin/ssh-copy-id: ERROR: No identities found

Possible [solutions](SSH identity files missing)?

## 26.FEB.2015

after following https://help.ubuntu.com/community/SSH/OpenSSH/Configuring

I did: https://help.ubuntu.com/community/SSH/OpenSSH/Keys

## NO-IP alternative

https://www.noip.com/support/knowledgebase/installing-the-linux-dynamic-update-client-on-ubuntu/
