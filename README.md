
# Solana Airdroper

[Solana Airdroper](https://scripts.bebralabs.com/solana-airdroper/) is a powerful tool for sending tokens to multiple Solana addresses. It supports both **EASY** mode (fixed amounts to a list of recipients) and **PRO** mode (custom amounts and tokens). The script simplifies token distribution, ideal for NFT creators and airdrop campaigns. With our script you can make solana tokens airdrops fast and easily

## How to Use:
1. [Download](https://scripts.bebralabs.com/solana-airdroper/) & unzip the script.
2. Install required dependencies:
   ```bash
   pip3 install base58
   ```
3. Fill airdrop.txt file for `easy mode` mode or airdrop.csv for `pro mode`. Examples are located in script folder.
4. Run the script in your terminal using the desired mode:
   - **EASY Mode**:
     ```bash
     python3 airdrop.py --token_address <token_address> --token_amount <amount>
     ```
   - **PRO Mode**:
     ```bash
     python3 airdrop.py --pro_mode ON
     ```

### Example:
- EASY Mode:
  ```bash
  python3 airdrop.py --token_address 8JyrJK8wmLT7tMG7JbtmzRVSe88YcdAeDMD7F9tMDiCf --token_amount 100
  ```
- PRO Mode:
  Add custom details to `airdrop.csv` and run:
  ```bash
  python3 airdrop.py --pro_mode ON
  ```

### Additional Resources:
+ [Full documentation & video guide](https://splashy-celery-733.notion.site/Solana-Airdroper-Setup-Guide-78df459f8b01415cb4855b05425f6df5)
+ [Buy with crypto](https://app.hel.io/pay/672a4626d1c14f7dd8989c5a)
+ [Buy with card](https://t.me/bebra_scripts/5)

---

Thank you for using Bebra Scripts. For help, contact our support: [https://t.me/bebralabs_bot](https://t.me/bebralabs_bot)

**Web3 Development Services** – [https://t.me/bebralabs_bot](https://t.me/bebralabs_bot)

Created with ❤️ by **Bebra Labs**  
[https://bebralabs.com](https://bebralabs.com)
