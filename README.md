# 🎧 HEADBRR

**A professional, high-fidelity headphone tester for Linux (Localhost Edition).**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF0055?style=for-the-badge)

HEADBRR is a minimalist, studio-grade audio diagnostic tool designed to test headphone frequency response, channel balance, driver phase, and noise floor. It runs as a local web server for maximum performance and cross-platform compatibility on Linux.

> [!NOTE]
> **Headcode (Terminal Version)** is coming soon! A pure CLI implementation of Headbrr for terminal power users.

## ✨ Features

- **📡 Frequency Analysis**: Pure sine wave generation from 20Hz to 20kHz with real-time HUD.
- **🔄 Exponential Sweep**: 10-second automated sweep for identifying driver resonance.
- **⚖️ Channel Check**: Isolated Left/Right testing to verify stereo imaging.
- **🌫️ Noise Generation**: Pro-grade White and Pink noise for driver burn-in and isolation testing.
- **🛠️ Phase Diagnostics**: In-Phase vs Out-of-Phase checks to detect wiring issues.
- **📊 VU Metering**: Real-time visual feedback of the output signal.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/chambtai-sys/Headbrr.git
   cd Headbrr
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Headbrr**:
   ```bash
   python app.py
   ```

4. **Access the HUD**:
   Open `http://localhost:5000` in your browser.

## 📁 Structure

```text
Headbrr/
├── app.py           # Flask Backend
├── templates/       
│   └── index.html   # Main HUD & Audio Engine
├── README.md        # Documentation
└── requirements.txt # Dependencies
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚀 Release Notes: Headbrr POWER

**Headbrr POWER** has been officially released! ⚡

This is the definitive terminal-native port for Microsoft PowerShell users. While the original Headbrr provides a high-fidelity web HUD, **Headbrr POWER** leverages pure .NET PCM synthesis to bring studio-grade diagnostics directly to the Windows terminal.

### 🔑 Key Differences
- **Native Execution**: No browser or local server required.
- **In-Memory Synthesis**: Generates raw 16-bit PCM streams without writing a single file.
- **PowerShell Optimized**: Features a built-in `hb` alias and interactive terminal UI.
- **Zero Dependencies**: Works out-of-the-box on any modern Windows system with PowerShell.

Check it out here: [chambtai-sys/Headbrr-POWER](https://github.com/chambtai-sys/Headbrr-POWER)
