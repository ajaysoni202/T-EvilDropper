

# T-EvilDropper

Telegram video (mp4) extension manipulation to redirect victims to malicious sites. In this POC, a Google Play Phishing Page is used as an example.



## 📌 Telegram Vulnerability Proof of Concept (POC)

### 🚀 Overview
This repository demonstrates a vulnerability in Telegram where an attacker can redirect a victim to a malicious site by sending a specially crafted video.

### ⚠️ Impact
- 🛑 The victim is tricked into opening a video sent via Telegram.
- 🔗 Upon clicking the video preview, the victim is redirected to a malicious website that can install malware or expose the victim's IP address, device model, etc.

### 🛠 Setup and Installation

```bash
git clone https://github.com/ajaysoni202/T-EvilDropper
cd T-EvilDropper
```

Now, edit the `tg.py` file using any text editor and fill in the required information:
- **Chat ID** [Link](https://t.me/BotFather)
- **Bot ID** [Link](https://t.me/userinfobot)
- **Custom HTML file** (for redirection or phishing page)

After saving the changes, run the following command to receive the video message:

```bash
python3 tg.py
```

### ⚖️ Disclaimer
This information is provided for **educational purposes only**. The author is not responsible for any misuse of this tool.

### 📢 More Information
For more details, follow me on Instagram and visit my website:

🌐 **Website:** [My Website](https://newlearninghub.in)

📷 **Instagram:** [Instagram](https://instagram.com/memeswalahacker)

💘 **Credit:** [Github](https://github.com/0x6rss)
