# topologia-rede-corporativa

## Errors resolutions
Error:
``` Err http://security.ubuntu.com oneiric-security Release.gpg
  Temporary failure resolving ‘security.ubuntu.com’ 
```
  
 Solution:
 
 do a 'ping 8.8.8.8' at the terminals of every machine that downloads packages and then, after a successful ping, run the apt-get commands one by one at the terminal.
 this is a common error at the inicialization of the DNS, DHCP and FTP machines.
