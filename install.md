Update the packages before starting the installation
```bash
sudo apt update && sudo apt upgrade -y && sudo apt autoremove -y
```

To start the installation, run the following script file
```bash
wget -O datagram-installer.sh https://gist.githubusercontent.com/datagram-dev/8ef3d7678dc828e45a65a3e955327736/raw/datagram-installer.sh && chmod +x datagram-installer.sh && sudo bash datagram-installer.sh ```
