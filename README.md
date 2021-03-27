# command-reset-ubuntu
command reset ubuntu


1/ Try configuring unconfigured packages:
```
sudo dpkg --configure -a
```

2/ Update the contents of the repositories
```
sudo apt-get update
```

3/ Try to fix missing dependencies:
```
sudo apt-get -f install
```

4/ Update all packages with new versions available:
```
sudo apt-get full-upgrade
```

5/ Reinstall Ubuntu desktop:
```
sudo apt-get install --reinstall ubuntu-desktop
```

6/ Remove unnecessary packages:
```
sudo apt-get autoremove
```

7/ Delete downloaded packages already installed:
```
sudo apt-get clean
```

8/ Reboot the system to see if the issue was resolved:
```
sudo reboot
```
