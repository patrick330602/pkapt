# ruapt

> rua!!!!

ruapt is a personal repository of mine, for Ubuntu 16.04, Ubuntu 18.04, Debian 9 and Kali Linux.

## Usage

In order to add this repository, install dependencies using the following commands:

```bash
sudo apt install lsb-release apt-transport-https
```

you can use the following ways to add key:

```bash
# from OpenPGP Keyserver
sudo apt-key adv --recv-key --keyserver pool.sks-keyservers.net 0x1C58C28D

# from my own server
wget -O - https://api.patrickwu.ml/public.key | sudo apt-key add -
```

then add repository using the follwing command:
 
```bash
sudo echo "deb https://apt.patrickwu.ml/ `lsb_release -c -s` main" >> /etc/apt/sources.list 
sudo apt update
```
