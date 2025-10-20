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

https://dashboard.datagram.network go to the address log in

![data](https://github.com/user-attachments/assets/7d05c663-6f63-491a-8c66-7c43359ff620)

Once they have your installation key, go back to the terminal and copy the key.

<img width="1660" height="319" alt="Ekran Resmi 2025-10-20 22 36 13" src="https://github.com/user-attachments/assets/c603fcc3-4747-4fa3-9144-a009fed30d64" />

Once they have your installation key, go back to the terminal, copy the key and confirm it.

This visual indicates the successful completion of the installation

<img width="186" height="45" alt="Ekran Resmi 2025-10-20 23 36 13" src="https://github.com/user-attachments/assets/8fdeca46-5983-4e29-9547-e6c10fd08d29" />

If it gives any error, run the following command in the datagram folder:

```bash
./datagram-cli-x86_64-linux run -- -key YOUR KEY
```
You need to get an output like in the previous image

You can use ( CTRL + A D ) to leave the terminal screen. It will continue to run in the background. To reconnect to the screen, you can connect with  ( screen -r datagram ) inix.

https://datagram.network/wallet?tab=licenses do not forget to check the connection status from the address.

![licanses](https://github.com/user-attachments/assets/659ad0c0-9816-402e-9404-3da006788755)

