Rassa Tools

Simple command-line tools for Termux.

Requirements

- Android
- Termux
- Internet connection

---

Installation

«Platform: Termux Only»

Option 1 — Copy Command (1/1)

Copy and paste the following command into Termux:

pkg update -y
pkg upgrade -y
pkg install git curl wget
git clone https://github.com/rassalee/rassa-tools 
cd rassa-tools 
chmod +x run
./run

---

Option 2 — One Click Copy

pkg update && pkg upgrade -y && pkg install -y git curl wget && git clone https://github.com/rassalee/rassa-tools && cd rassa-tools && chmod +x run && ./run

---

Features

- Automatic dependency checking
- Automatic installation
- Automatic update
- Download latest script from server
- Easy to use

---

Run Again

After installation, simply run:

rassa

---

Update

git pull

---

License

This project is provided as-is for educational and personal use.
