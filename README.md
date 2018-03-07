# Bash ITNS info 
Bash ITNS info is a simple terminal "widget" that will display on right top corner some statistics about mining on ITNSpool.net and exchange rate directly on terminal.  
  
This shouldn't impact your terminal usability

# Screenshot
![ScreenShot](https://i.imgur.com/AjowprU.png)
(Unicorn not related!)

# Variables
The only mandatory variable to be modified is "wallet"!  
Few other variables might be changed as described at the beginning of the code.

# Installation
```bash
 wallet="WALLET_HERE"
 wget https://raw.githubusercontent.com/itnsmyname/bash-itns-info/master/.itns_functions -O ~/.itns_functions && \
 sed -i 's/WALLET_HERE/$wallet/' ~/.itns_functions
 echo "source ~/.itns_functions" >> ~/.bashrc && \
 source ~/.itns_functions
 ```

# Usage
After the installation and properly adjusted the "wallet" variable type ```coin```  
If you don't want to use the widget but only want to see the values on demand just type ```coinfunction```  

To stop the widget simply type ```fg``` and then CTRL+C .

# Uninstall
To uninstall copy/paste the following
```bash
rm -rf ~/.itns_functions
sed -i '/itns_functions/d' .bashrc
```
# Donation
If you want to offer me a virtual beer, feel free to do so!

BTC: 182K9dsSyE1n8PKye8znJudGEerW7mNm85
LTC: LPqVBp32rgdUdkesD16VXnwSXAUCgRbcGZ
ETH: 0x25657378Fc1dC8A4065476b38DFa418E646EA7f9
ITNS: iz4vDL8dymm76jS7dRw7VPLmBEUSwzWXtQPViGnfqE29HrdAker7e12KBmhjRd3AD6MTbuZuMy4rdcFAmGoEJPvp1vKBa8xuK
