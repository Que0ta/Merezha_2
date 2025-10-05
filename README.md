# 💬 Flask-SocketIO Web Chat

A real-time web chat application built with **Flask** and **Socket.IO**, providing instant messaging between users through a lightweight Python backend.  
It’s simple to set up, fully extensible, and can be hosted on any platform that supports Python (Render, Railway, VPS, etc.).

---

## 🚀 Features

- ⚡ Real-time messaging using **Flask-SocketIO**
- 👥 Multi-user chat rooms
- 🧠 Lightweight Flask backend
- 🔒 Secure WebSocket connection
- ☁️ Easy deployment to cloud services (Render in our way)

---

## 🧱 Tech Stack

| Component | Description |
|------------|-------------|
| **Backend** | Flask + Flask-SocketIO |
| **Frontend** | None |
| **Server** | Render |
| **Language** | Python 3.11+ |

---

## ⚙️ Project Settup

## 📥 1. Fork the Repository
In ```server.py``` you can change the ```secret key``` config at the start! 

## 2. Create a Render account.
You can see the hosting[right here](https://render.com/) 

## ⚙️ 3. Create a new Web Service
* Click “New +” → Web Service
* Copy your repository link and put it down in "Public git repository" input field.
* Then u will need to configure your project:
  - Build command: ```pip install -r requirements.txt```
  - Start command: ```python server.py```
  - Choose free service & **deploy**✔️
* Wait till the app will be **live**.

## 🤝 4. Let's try our clients connections.
* Now you can easily get the render link in the top section.
* Put it into client's ```server_url```  and check your connection 😃

> [!CAUTION]
> Don't forget **to ping or visit your server's URL**, in order to keep your server live, because hosting after inactivity can go to sleep, so you will need to ping it 1 more time to get it running.



