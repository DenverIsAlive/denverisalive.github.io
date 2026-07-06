<p align="center">
  <img src="https://i.ibb.co/f7fLjcX/Tataplay.png" width="280" alt="TataPlay Logo"/>
</p>

<h1 align="center">TataPlay M3U Playlist Generator</h1>

<p align="center">
  <strong>A PHP script to generate an M3U playlist from <a href="https://watch.tataplay.com">watch.tataplay.com</a> with 8-day catchup support.</strong>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL-blue.svg" alt="License: GPL"/></a>
  <a href="https://t.me/DenverIsAlivee"><img src="https://img.shields.io/badge/Telegram-Join%20Channel-blue?logo=telegram" alt="Telegram"/></a>
  <img src="https://img.shields.io/badge/PHP-8.1%2B-purple" alt="PHP 8.1+"/>
</p>

<p align="center">
  🌟 If you find this helpful, consider giving this repository a <strong>Star</strong>! ⭐
</p>

---

## 📋 Requirements

- An **active TataPlay subscription**
- A **working human brain** 🧠

---

## 🚀 Getting Started

### Step 1 — Set Up a Local PHP Server

Choose the option that fits your device:

• Platform | Tool | Download 🐼

       |----------|------|----------|

📱 Android (Mobile) | KSWEB PRO v3.988

‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ **[Download APK](https://apkmodct.com/ksweb/)**

💻 Windows (PC) | XAMPP or Autho IPTV

‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎  **[Download Files for Pc](https://www.apachefriends.org/download.html)**

---

### Step 2 — Download & Extract the Script

**[⬇️ Download Script ZIP](https://github.com/DenverIsAlive/TP/archive/refs/heads/main.zip)**

Extract all files into the `htdocs` folder, inside a subfolder named `tataplay`:

```
📂 FileManager
└── 📂 htdocs/
    └── 📂 tataplay/
        ├── 📄 .htaccess
        ├── 📄 functions.php
        ├── 📄 hmac.php
        ├── 📄 index.php
        └── 📄 ...
```

Once extracted, open **KSWEB** (or **XAMPP** on PC) and start the **Localhost** and **Apache** servers. The setup is complete and the script is ready to use.

---

### Step 3 — Log In

Open the login page in your browser:

[http://localhost:8000/tataplay/login.php](http://localhost:8000/tataplay/login.php)

- You can Also Use default ip url
[http://127.0.0.1:8000/tataplay/login.php](http://127.0.0.1:8000/tataplay/login.php)

> 💡 Your **Wi-Fi IP URL** is displayed on the KSWEB home screen. Use port `8000` for mobile & TV, and port `80` for PC.

Log in using your **TataPlay Subscriber ID**, then enter the **OTP** sent to your registered mobile number.

> ⚠️ The account used must be an **active subscription**.

---

### Step 4 — Access Your M3U Playlist

Use the following URL in **Tivimate**, **NS Player**, **OTT Navigator**, or any IPTV Player:

[http://localhost:8000/tataplay/Playlist.m3u](http://localhost:8000/tataplay/Playlist.m3u)

Use the following URL in **Autho IPTV**, or any IPTV Player for PC:
[http://localhost:80/tataplay/Playlist.m3u](http://localhost:80/tataplay/Playlist.m3u)


You can also copy the Playlist URL directly from `index.php`. Enjoy your TataPlay channels! 🎉

---

## ✨ Features

### Core
- 📺 All TataPlay channels included
- 🎬 Multi-quality streaming support
- 🔌 Plug & play — minimal configuration required
- 🌐 Works on all compatible IPTV platforms
- 📖 Clean, well-commented code — great for learning PHP authentication flows

### Advanced
- ⏪ **8-day catchup support** for eligible channels
- 🔑 Automatic token extraction
- 🗃️ Well-structured cache system
- 🛡️ DRM key support for select channels (fallback for deactivated accounts)

---

## ⚠️ Warnings

- This script is intended for **educational purposes only**
- **Do not sell this script** — it is 100% free
- Use responsibly and only with your own active account

---

## 📄 Disclaimer

> This project is for educational purposes only, to demonstrate authentication flows and IPTV streaming mechanics in PHP. I am not responsible for any misuse of this code or any revenue loss caused to the concerned parties and service owners. This code is protected under the [GPL License](LICENSE).

---

<p align="center">
  Made with ❤️ by <a href="https://t.me/DenverIsAlivee">@Denver1769</a> &nbsp;|&nbsp; © 2022–26
</p>

<!-- DO NOT REMOVE THIS CREDIT -->
<!-- © 2022-26 @Denver1769 -->
