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
![Ubuntu Logo](Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F2JG2WtN9P3Hm437FJZ3R%252Fuploads%252F5JQwPk3wCUO0Z3uccwe8%252Fdashboard%2520wallet%2520markup.png%3Falt%3Dmedia%26token%3D2dfee3b6-d498-4279-a3da-ac5f7cba115b&width=768&dpr=4&quality=100&sign=e36394fa&sv=2)
