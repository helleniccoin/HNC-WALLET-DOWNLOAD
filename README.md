# HELLENIC COIN (HNC)

   WALLET-DOWNLOAD  --- helleniccoin.conf instractions

Ready compiled hnc wallets and daemons


# Windows 

Windows Wallet ---> helleniccoin-qt-windows.zip

Windows Daemon ---> helleniccoin-daemon-windows.zip


# Linux 

Linux Wallet  ---> helleniccoin-qt-linux.tar.gz

Linux Daemon  ---> helleniccoin-daemon-linux.tar.gz

#Use Ubuntu 18.04 LTS.

#Update your Ubuntu machine.
sudo apt-get update
sudo apt-get upgrade

#Install the required dependencies.
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev

sudo apt-get install libminiupnpc-dev libzmq3-dev libprotobuf-dev protobuf-compiler unzip

#Install Berkeley DB.
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev


# Mac

MacOs Wallet ---> helleniccoin-qt.dmg

MacOs Tools  ---> helleniccoin-tools-macos.tar.gz

# helleniccoin.conf

Paste the following lines in helleniccoin.conf.

rpcuser=rpc_helleniccoin
rpcpassword=Your_strong_rpc_password
rpcallowip=127.0.0.1
listen=1
server=1
daemon=1
maxconnections=64
externalip=REPLACE_WITH_EXTERNAL_IP_OF_VPS
addnode=node1.helleniccoin.gr
addnode=node2.helleniccoin.gr
