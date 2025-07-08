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

**accounts.txt**

```
your_private_key_1
your_private_key_2
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
