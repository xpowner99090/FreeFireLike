# 🚀 Free Fire Like API

<p align="center">
  <img src="./logo.png" width="140" alt="XP OPU Logo">
</p>

<h1 align="center">FREE FIRE LIKE API</h1>

<p align="center">
  ⚡ Ultra Fast Async Like API Using Flask + AES + Protobuf
</p>

<p align="center">
  <a href="https://t.me/XP_OWNER99">
    <img src="https://img.shields.io/badge/Telegram-XP_OWNER99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>

  <a href="https://xpopu.top">
    <img src="https://img.shields.io/badge/Website-xpopu.top-black?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</p>

---

# ✨ Features

- ⚡ Ultra Fast Async Request System
- 🔐 AES CBC Encryption
- 📦 Protobuf Serialization
- 🌍 Multi Region Support
- 🧠 Smart Token Loader
- 🚀 Flask REST API
- 📊 Real Like Count Response
- 🔥 OB53 Supported
- 🛡 Full Error Handling
- ⚙️ VPS Optimized

---

# 🌍 Supported Regions

| Region | Code |
|--------|------|
| Bangladesh | BD |
| India | IND |
| Brazil | BR |
| United States | US |
| North America | NA |
| SAC | SAC |

---

# 📂 Project Structure

```bash
project/
│
├── app.py
│
├── like_pb2.py
├── like_count_pb2.py
├── uid_generator_pb2.py
│
├── token_bd.json
├── token_br.json
├── token_ind.json
│
├── requirements.txt
│
└── README.md
```

---

# 📦 Requirements

## Install Packages

```bash
pip install -r requirements.txt
```

## requirements.txt

```txt
flask
aiohttp
requests
pycryptodome
protobuf
```

---

# 📁 Token Files

## token_bd.json

```json
[
  {
    "token": "YOUR_JWT_TOKEN"
  },
  {
    "token": "YOUR_JWT_TOKEN_2"
  }
]
```

## token_br.json

```json
[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]
```

## token_ind.json

```json
[
  {
    "token": "YOUR_JWT_TOKEN"
  }
]
```

---

# ▶️ Run Server

```bash
python app.py
```

Server Running On:

```bash
http://127.0.0.1:5000
```

---

# ⚙️ Production Deployment

# Gunicorn

```bash
gunicorn -w 4 -k gthread -b 0.0.0.0:5000 app:app
```

# PM2

```bash
pm2 start app.py --interpreter python3 --name ff-like-api
```

# Supervisor

```bash
sudo nano /etc/supervisor/conf.d/fflike.conf
```

## Config

```ini
[program:fflike]
directory=/root/project
command=python3 app.py
autostart=true
autorestart=true
stderr_logfile=/var/log/fflike.err.log
stdout_logfile=/var/log/fflike.out.log
```

## Restart Supervisor

```bash
sudo supervisorctl reread
sudo supervisorctl update
sudo supervisorctl restart fflike
```

---

# 📌 API Endpoint

```bash
GET /like?uid={uid}&server_name={region}
```

---

# ✅ Example Request

```bash
https://your-domain.com/like?uid=123456789&server_name=BD
```

---

# ✅ Example Response

```json
{
  "LikesGivenByAPI": 154,
  "LikesafterCommand": 2034,
  "LikesbeforeCommand": 1880,
  "PlayerNickname": "XP OPU",
  "UID": 123456789,
  "status": 1
}
```

---

# 📊 Response Explanation

| Key | Description |
|-----|-------------|
| LikesGivenByAPI | Total Likes Added |
| LikesafterCommand | Likes After Request |
| LikesbeforeCommand | Likes Before Request |
| PlayerNickname | Player Name |
| UID | Player UID |
| status | 1 = Success |
| status | 2 = Failed |

---

# 🔥 Performance

- 250 Async Requests Per Command
- Multi Token Rotation
- Low RAM Usage
- High Speed Response
- VPS Optimized
- Fast Like Delivery

---

# 🛠 Built With

- Python
- Flask
- AsyncIO
- AioHTTP
- Requests
- PyCryptodome
- Protobuf

---

# 🧠 Encryption

This API Uses:

- AES CBC Encryption
- Protobuf Encoded Binary Requests
- Bearer Token Authentication

---

# 👨‍💻 Developer

## 📢 Telegram

<p align="left">
  <a href="https://t.me/XP_OWNER99">
    <img src="https://img.shields.io/badge/Telegram-XP_OWNER99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white">
  </a>
</p>

## 🌐 Website

<p align="left">
  <a href="https://xpopu.top">
    <img src="https://img.shields.io/badge/Website-xpopu.top-black?style=for-the-badge&logo=google-chrome&logoColor=white">
  </a>
</p>

---

# 🌐 Official Website

https://xpopu.top

---

# ⚠ Disclaimer

This project is made for educational purposes only.

The developer is not responsible for any misuse of this project.

Use at your own risk.

---

# ⭐ Support

If you like this project:

```bash
⭐ Star This Repository
🍴 Fork The Repository
📢 Share With Friends
```

---

# ❤️ Thanks For Using

<p align="center">
  MADE WITH ❤️ BY XP OPU
</p>
