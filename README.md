# ruapt

> rua!!!!

ruapt is a personal repository of mine, for Ubuntu 16.04, 18.04 and Debian 9.

## Usage

In order to add this repository, install `add-apt-repository` by install `software-properties-common` on your debian or ubuntu:

```bash
sudo apt install software-properties-common
```

Then add key and repository and update the repo using the following commands:

```bash
wget -O - https://apt.patrickwu.ml/pkapt.key | sudo apt-key add -
sudo add-apt-repository https://apt.patrickwu.ml/
sudo apt update
```
