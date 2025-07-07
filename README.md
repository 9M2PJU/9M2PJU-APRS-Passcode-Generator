# 📡 9M2PJU APRS Passcode Generator

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fpass.hamradio.my)](https://pass.hamradio.my)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://hamradio.my)

> A lightweight, user-friendly web tool for generating APRS passcodes from amateur radio callsigns. Try it live at [pass.hamradio.my](https://pass.hamradio.my)!



## 🌟 Features

- **Instant Passcode Generation**: Generate APRS passcodes from any valid callsign
- **User-Friendly Interface**: Clean, modern design with intuitive controls
- **Mobile Responsive**: Works perfectly on all devices
- **Visual Feedback**: 
  - Callsigns displayed in blue with uppercase formatting
  - Passcodes highlighted in red for clarity
  - Real-time validation and error checking
- **9M2PJU APRS Passcode Generator Android App**: Download [here](https://github.com/9M2PJU/9M2PJU-APRS-Passcode-Generator/raw/refs/heads/main/9M2PJU-APRS-Passcode-Generator.apk)

## 🚀 Quick Start

1. Visit [pass.hamradio.my](https://pass.hamradio.my)
2. Enter your amateur radio callsign
3. Click "Generate"
4. Your APRS passcode will be instantly displayed

### 📌 Embed on Your Site

Add this responsive iframe to your website:

```html
<iframe 
  src="https://pass.hamradio.my" 
  style="width: 100%; height: 500px; border: none;" 
  allowfullscreen
></iframe>
```

## 🔧 Technical Details

### What is APRS?

APRS (Automatic Packet Reporting System) is a digital communications protocol for amateur radio. It enables real-time sharing of:
- Geographic positions
- Weather station data
- Short messages
- Other data

### Passcode Algorithm

The APRS passcode is generated through:
1. SSID removal (e.g., "-1" from callsign)
2. Uppercase conversion
3. Bitwise operations:
   - XOR operations
   - Bit shifting of ASCII values
   - Combination with constant 0x73
4. Generation of 16-bit unique identifier

### Use Cases

- ✅ Beacon Authentication
- ✅ APRS-IS Network Access
- ✅ Digipeater Validation
- ✅ iGate Configuration
- ✅ Custom APRS Services

## 💻 Development

### Prerequisites

- Basic knowledge of:
  - HTML5
  - CSS3
  - JavaScript (ES6+)
- Git for version control
- GitHub account for contributions

### Contributing

We welcome contributions! Here's how:

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

## 📄 License

This project is licensed under the GNU Affero General Public License v3.0 - see the [LICENSE](https://www.gnu.org/licenses/agpl-3.0.html) file for details.

## 🙏 Acknowledgments

- Created with ❤️ by [9M2PJU](https://hamradio.my)
- Special thanks to [JollyJolli](https://github.com/JollyJolli) for contributions

## 📬 Contact

- Website: [hamradio.my](https://hamradio.my)
- GitHub: [@9M2PJU](https://github.com/9M2PJU)

---

<p align="center">
  Made with ❤️ for the Amateur Radio Community
</p>
