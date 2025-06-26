# APK_Bilder - Payload Injector & APK Binder

## 🔥 Features:
- Generate Android Meterpreter Payload (Python & Bash)
- Bind Payload with Any APK
- Auto Sign APK
- Auto Fix Errors (Internet, Keystore, Smali Path)
- Clean UI for Beginners

## 🚀 Installation:
```bash
pkg update -y
pkg install git -y
git clone https://github.com/CCU-BNCC/apk_bilder
cd apk_bilder
bash install.sh




---

## ✅ **install.sh Example:**  

```bash
#!/bin/bash

echo "🔗 Updating..."
pkg update -y && pkg upgrade -y

echo "📦 Installing Dependencies..."
pkg install metasploit -y
pkg install apktool -y
pkg install apksigner -y
pkg install openjdk-17 -y
pkg install git -y
pkg install python -y

echo "✅ Installation Complete."
echo "🚀 Run: bash apk_bilder.sh"


