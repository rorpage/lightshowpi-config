# lightshowpi-config
Configuration for lightshowpi and rocktheirv

---

## Step 0 – Update Raspian
Before you get started update and upgrade raspian to the latest:
```
sudo apt-get update
sudo apt-get upgrade
```

## Step 1 - Download LightShow Pi

### Install git (if you don't already have it)
```bash
sudo apt-get install git-core
```

### Clone the repository to /home/pi/lightshowpi
```bash
cd ~
git clone https://togiles@bitbucket.org/togiles/lightshowpi.git
```

### Grab the stable branch
```bash
cd lightshowpi
git fetch && git checkout stable
```

## Step 2 - Install LightShow Pi
```bash
cd /home/pi/lightshowpi
sudo ./install.sh
sudo reboot
```
