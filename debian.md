## Pour changer définitivement le nom de la machine sous Debian 11
```
sudo hostnamectl set-hostname nouveau_nom
sudo nano /etc/hosts
sudo systemctl restart systemd-hostnamed
hostnamectl
```
