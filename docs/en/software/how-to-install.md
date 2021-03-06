# How to install nch

## The latest version

The latest  testnet version is testnet-v1.2.0

## Server configuration

Recommended server configuration:

* CPU cores: 2
* RAM: 4GB+
* Disk: 100GB+ SSD
* OS: Ubuntu 18.04
* Bandwidth:10Mbps
* Open ports: 26656 and 26657

## Installation

### 1. Setting up a development environment

* Install dependence

```bash
sudo apt-get update
sudo apt-get install git gcc cmake make golang-statik
```

To install and configure go, click [here](../software/go-install.md)

### 2. Build nch from source code

```bash 
# Get nch source code
git clone https://github.com/netcloth/netcloth-chain.git
cd netcloth-chain && git checkout  testnet-v1.2.0


# Install statik
sudo apt-get update
sudo apt-get install golang-statik

# Compile and install
make install

# check version
nchd version
nchcli version
```

Congratulations! You have installed nchcli successfully. Now you can build a full-node on NetCloth testnet. [Click here](../get-started/how-to-join-testnet.md)
