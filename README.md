# Cotainner
```
sudo apt update -y
sudo apt install openssh-server -y
sudo apt install nano -y
```
```
sudo systemctl start ssh
sudo systemctl enable ssh

```
```
sudo ufw allow ssh
sudo ufw enable
sudo ufw status
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
sudo systemctl status ssh
```
```
sudo systemctl restart ssh
```
```
ssh root@172.252.13.70
```
