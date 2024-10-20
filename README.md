## Intel Incentivized Testnet
### Install Packages
```console
sudo apt update & sudo apt upgrade -y
sudo apt install ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev curl git wget make jq build-essential pkg-config lsb-release libssl-dev libreadline-dev libffi-dev gcc screen unzip lz4 -y
```
### Nodejs & npm
```console
curl -sL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt-get install -y nodejs
node -v
npm -v
```
### Install the Rivalz Node CLI
```console
npm i -g rivalz-node-cli
```
### Run rClient
```console
rivalz run
```

