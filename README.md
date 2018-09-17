# ruapt

> rua!!!!

ruapt is a debian package repository for my packages and wslutilities.

## Usage

In order to add this repository, install dependencies using the following commands:

```bash
sudo apt install apt-transport-https
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
# For stable packages
echo "deb https://apt.patrickwu.ml/ stable main" | sudo tee -a /etc/apt/sources.list 
# For unstable packages
echo "deb https://apt.patrickwu.ml/ unstable main" | sudo tee -a /etc/apt/sources.list 

sudo apt update
```
