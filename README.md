# Axo's Pomodoro Timer
Axo's Pomodoro Timer is a simple study timer based on proven learning methods: the Pomodoro Technique (25/5) and the Ultradian Rhythm (90/20). These cycles maximize focus, memory, and productivity by balancing deep work with effective rest. Stay sharp, study smarter, and boost learning.

** Actually i made it for my personal i am so lazy to manualy set the timer in my phone ** 


# Pomodoro Timer ⏱️  

A simple **Pomodoro-style timer app** with two modes:  
- **25/5 minutes** (Work / Break)  
- **80/20 minutes** (Work / Break)  
- **1 min / 30 sec** (Test / Quick break)  

Supports both **Linux Desktop** and **Android (APK)**.  

---

## ✨ Features
- Work/Break timer system  
- Alarm beep when time ends  
- Continuous notifications every 15 seconds (Android)  
- Vibration support (Android)  
- Command line arguments to start timers directly (Linux)  
- Exit and Next buttons to control workflow  

---

## 🖥️ Linux Version  

### 🔧 Requirements
- Python 3.10+  
- Tkinter  
- Sox (for beep sound)  

Install dependencies:

```bash
sudo apt-get update
sudo apt-get install python3 python3-tk sox


▶️ Run the App

Clone this repository:

git clone https://github.com/yourusername/pomodoro-timer.git
cd pomodoro-timer

python3 timer_app.py

# 25/5 mode
python3 timer_app.py 25

# 80/20 mode
python3 timer_app.py 80

# 1/0.5 mode
python3 timer_app.py 1


---

📱 Android Version
🔧 Requirements

Linux system with Buildozer

Cython, Git, Java JDK, Android SDK & NDK

Install build tools (Ubuntu/Debian example):


```bash
sudo apt-get install -y python3-pip python3-setuptools git zip unzip \
openjdk-17-jdk zlib1g-dev libncurses5-dev libstdc++6 libffi-dev \
libssl-dev automake autoconf libtool pkg-config cmake
pip3 install --user buildozer cython



---
