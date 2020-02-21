# Guide for QUISH Masternode Setup:


For **Ubuntu 16.04**
```
wget -q https://raw.githubusercontent.com/quishtv/Auto-MN-Setup/master/QUISH_16.04.sh
sudo chmod +x QUISH_16.04.sh
./QUISH_16.04.sh
```
***

For **Ubuntu 18.04**
```
wget -q https://raw.githubusercontent.com/quishtv/Auto-MN-Setup/master/QUISH_18.04.sh
sudo chmod +x QUISH_18.04.sh
./QUISH_18.04.sh
```
***

Do you want me to generate a masternode private key for you?[y/n]

- If you don't want to generate a masternode private key press **n**.

  > Next ask for Private key:
  
  > Enter your private key: Paste Your Masternode Private Key
  
  > Confirm your private key: Again Paste Your Masternode Private Key for confirmation

**OR**

- If you want to generate a masternode private key press  **y**.

 Enter VPS Public IP Address: Paste your VPS Address

 Wait till Node is fully Synced with blockchain.

`QUISH-cli getinfo`

When Node is Fully Synced enter the command below to check the masternode status.

`QUISH-cli getmasternodestatus`

You will get Masternode Successfully Started