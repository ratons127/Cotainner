# Cotainner
```
sudo apt update -y
sudo apt install openssh-server -y
sudo apt install nano -y
```
```
nano /etc/ssh/sshd_config
```
```
PermitRootLogin yes
PasswordAuthentication yes
```
```
nano /etc/ssh/sshd_config
```

```
sudo systemctl restart ssh
```
```
ssh root@172.252.13.70
```
