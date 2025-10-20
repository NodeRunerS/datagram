Before starting the installation, update the packages and install screen to keep terminal sessions running in the background.
```bash
sudo apt update && sudo apt install screen -y
```
Create a screen in the background
```bash
screen -S datagram
```

To start the installation, run the following script file
```bash
wget -O datagram-installer.sh https://gist.githubusercontent.com/datagram-dev/8ef3d7678dc828e45a65a3e955327736/raw/datagram-installer.sh && chmod +x datagram-installer.sh && sudo bash datagram-installer.sh
```
The installation will request a license key from you

