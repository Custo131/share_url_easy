# 📱 Swipe-to-Laptop URL Sender

This project allows you to send a URL from your Android phone to your laptop with a simple swipe gesture. It's perfect for when you open something interesting on your phone and want to instantly view it on a bigger screen — without having to type or search for it again.

## 🔧 How It Works

- A **Kivy mobile app** lets you enter a URL and swipe right to send it.
- A **FastAPI server** running on your laptop listens for incoming requests.
- When the URL is received, it automatically opens in the laptop's browser.

## 📦 Technologies Used

- Python
- Kivy (for Android app)
- FastAPI (for laptop server)
- Webbrowser module (for opening URLs on the laptop)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/swipe-to-laptop.git
cd swipe-to-laptop
