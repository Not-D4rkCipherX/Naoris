# Naoris Node Protocol MINING + AUTO RFER BOT

- Register Here : [Naoris Protocol Testnet](https://naorisprotocol.network/testnet)
- Dwonload Wallet: [Naoris Protocol Wallet](https://chromewebstore.google.com/detail/naoris-protocol-wallet/dbgibbbeebmbmmhmebogidfbfehejgfo)
- Dwonload Extension: [Naoris Protocol Browser Security Node](https://chromewebstore.google.com/detail/naoris-protocol-browser-s/cpikalnagknmlfhnilhfelifgbollmmp)
- Use Code: VBYSn6M90L6De0DB

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Add to Whitelist
  - Auto Send Ping Every 25 Seconds
  - Multi Accounts With Threads

- Note: Points Not Increase? pending bruh. please be patient.

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation
```bash
   git clone https://github.com/Not-D4rkCipherX/Naoris.git
   ```
   ```bash
   cd Naoris
   ```
   ```bash
   pip install -r requirements.txt
   ```
```bash
nano accounts.json
```

## Configuration

### Screenshots

<div style="text-align: center;">
  <h4><strong>Device Hash</strong></h4>
  <img src="image.jpg" alt="Image" width="500"/>
</div>

- **accounts.json:** You will find the file `accounts.json` inside the project directory. Make sure `accounts.json` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
  [
      {
          "Address": "Your evm address 1",
          "deviceHash": "Your device hash 1"
      },
      {
          "Address": "Your evm address 2",
          "deviceHash": "Your device hash 2"
      }
  ]
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py
```

## FOR AUTO REFER
```bash
npm i
```
```bash
node autoref.js
```
Created accounts will be added on accounts.json and accounts.txt file
###PROXY FORMAT :
ip:port # Default Protcol HTTP.
protocol://ip:port
protocol://user:pass@ip:port
