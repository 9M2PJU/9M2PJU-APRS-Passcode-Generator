# 📡 9M2PJU APRS Passcode Generator

[![Live Site](https://img.shields.io/website?url=https%3A%2F%2Fpass.hamradio.my&style=for-the-badge)](https://pass.hamradio.my)
[![Made With ❤️](https://img.shields.io/badge/Made%20With-%E2%9D%A4-red?style=for-the-badge)](https://hamradio.my)
[![Android App](https://img.shields.io/badge/Android-Download-green?style=for-the-badge&logo=android)](https://github.com/9M2PJU/9M2PJU-APRS-Passcode-Generator/raw/refs/heads/main/9M2PJU-APRS-Passcode-Generator.apk)

> ⚡ A fast, friendly web tool to generate APRS-IS passcodes from amateur radio callsigns.  
> Live at 🌍 [pass.hamradio.my](https://pass.hamradio.my)

---

## 🌟 Features

- ⚡ Instant APRS passcode generation  
- 📱 Responsive layout for mobile & desktop  
- 🧠 Real-time validation with visual feedback  
- 🔵 Callsigns styled in **blue**, **UPPERCASE**  
- 🔴 Passcodes shown in **bold red**  
- 📲 Android app included  

---

## 🚀 Get Started

🔗 Visit: [https://pass.hamradio.my](https://pass.hamradio.my)

1. Type your **valid callsign**
2. Click **Generate**
3. View your **APRS passcode** instantly

---

## 🧩 Embed in Your Website

```html
<iframe 
  src="https://pass.hamradio.my" 
  style="width: 100%; height: 500px; border: none;" 
  allowfullscreen
></iframe>
```

---

## 📡 What is APRS?

[APRS](https://en.wikipedia.org/wiki/Automatic_Packet_Reporting_System) (Automatic Packet Reporting System) is a digital radio protocol used in [amateur radio](https://en.wikipedia.org/wiki/Amateur_radio) for:

- 🔍 Position tracking  
- 🌦️ Weather telemetry  
- 💬 Messaging & bulletins  
- 🔁 Repeater beacons & more  

---

## 🔐 How Passcodes Work

APRS-IS requires a numeric **passcode** for authentication.  
This tool uses the standard algorithm:

1. Strip SSID (`-1`, `-7`, etc.)  
2. Convert callsign to uppercase  
3. Bitwise operations per character:  
   - XOR with constants  
   - Bit shifts  
   - Merge with `0x73`  
4. Return 16-bit APRS passcode  

Example:  
- Input: `9W2XYZ-9`  
- Processed: `9W2XYZ`  
- Output: `passcode = 56789` *(example)*

---

## 🛠️ Developer Guide

### 🧰 Requirements

- HTML, CSS, JavaScript (ES6+)  
- Basic Git knowledge  

### 🔧 Setup

```bash
git clone https://github.com/9M2PJU/9M2PJU-APRS-Passcode-Generator.git
cd 9M2PJU-APRS-Passcode-Generator
open index.html
```

---

## 🤝 Contribute

All contributions welcome!

```bash
# Step 1: Fork
git checkout -b feature/NewFeature

# Step 2: Commit changes
git commit -m "Add: NewFeature"

# Step 3: Push to GitHub
git push origin feature/NewFeature

# Step 4: Open a Pull Request
```

---

## 📲 Android App

📥 [Download APK](https://github.com/9M2PJU/9M2PJU-APRS-Passcode-Generator/raw/refs/heads/main/9M2PJU-APRS-Passcode-Generator.apk)

- Offline use supported  
- Fast & lightweight  

---

## 📄 License

Released under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html)

Free to use, improve, and redistribute with attribution.

---

## 🙏 Credits

- Built with ❤️ by [9M2PJU](https://hamradio.my)  
- Thanks to [@JollyJolli](https://github.com/JollyJolli) for early support  

---

<p align="center">
  🌐 Empowering the Amateur Radio Community — One Call at a Time
</p>
