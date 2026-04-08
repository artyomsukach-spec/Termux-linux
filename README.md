# Termux-linux
A Python-based manager for Termux to easily install and manage 18+ Linux distributions via proot-distro. Features a simple interactive menu for one-click setup.
# Termux-Linux Manager

This script simplifies the process of installing Linux distributions in Termux. Instead of typing long commands, you just pick a number from the menu.

### **Features**
* **One-click install** for 18 different distros (Ubuntu, Arch, Debian, etc.).
* **Auto-setup**: Automatically updates packages and installs `proot-distro`.
* **Lightweight**: Written in pure Python.

### **How to Install and Run**

1. **Update Termux & Install Git:**
   ```bash
   pkg update && pkg upgrade -y
   pkg install git python -y
   git clone [https://github.com/artyomsukach-spec/Termux-linux](https://github.com/artyomsukach-spec/Termux-linux)
cd Termux-linux
