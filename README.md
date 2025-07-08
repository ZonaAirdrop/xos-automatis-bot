# xos-automatis-bot

■ Auto Account Info Detection  
■ Proxy Support  
   ├─ Public Proxy via Proxyscrape  
   ├─ Private Proxy Support  
   └─ No Proxy Mode  
■ Proxy Rotation (Optional)  
■ Auto Daily Check-In  
■ Auto Perform Draw  
■ Auto Faucet Claim (Requires 2Captcha Key)  
■ Auto Wrap & Unwrap  
■ Auto Token Swapping  
■ Multi-Account Support with Threading  

## 🔧 How to Use

📁 **1. Setup Project Directory**

```bash
git clone https://github.com/ZonaAirdrop/xos-automatis-bot.git
cd xos-automatis-bot
```

📦 **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

📝 **3. Prepare Required Files**

**.env**

```
PRIVATE_KEYS=your_private_key_1,your_private_key_2
CAPTCHA_KEY=your_2captcha_api_key (Optional)
```

**2captcha\_key.txt** *(optional)*

```
your_2captcha_api_key
```

**proxy.txt** *(optional)*

```
ip:port
http://ip:port
http://user:pass@ip:port
```

🚀 **4. Run the Bot**

```bash
python bot.py
```

## 🔐 Security Notice

> **Always prioritize the security of your private key and RPC endpoints.**
> This bot interacts with blockchain networks and performs automated transactions, so improper handling of sensitive credentials can lead to irreversible asset loss.

### 🚫 Disclaimer

This software is provided for **educational and testing purposes only**.
The maintainers are **not responsible** for any loss, damage, or misuse caused by the use of this tool.

> By using this bot, you agree that you understand the risks associated with blockchain automation, including but not limited to transaction fees, delays, and unexpected behavior due to network congestion or smart contract changes.

For updates and support: https://t.me/ZonaAirdr0p
