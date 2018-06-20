# ruapt

> rua!!!!

ruapt is a personal repository of mine, for Ubuntu 16.04, Ubuntu 18.04, Debian 9 and Kali Linux.

## Usage

In order to add this repository, install dependencies using the following commands:

```bash
sudo apt install software-properties-common apt-transport-https
```

Then add key and repository and update the repo using the following commands:

```bash
wget -O - https://apt.patrickwu.ml/pkapt.key | sudo apt-key add -
sudo add-apt-repository https://apt.patrickwu.ml/
sudo apt update
```
