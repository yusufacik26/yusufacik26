<h1 align="center">🤖 AI Mini Bot (Windows Edition)</h1>

<p align="center">
  <b>Physical AI Assistant</b> • <b>Computer Vision</b> • <b>IoT & ESP32</b>
</p>

<p align="center">
  <a href="https://github.com/yusufacik26/AI-Mini-Bot">
    <img src="https://komarev.com/ghpvc/?username=yusufacik26-aiminibot&label=Project%20views&color=0e75b6&style=flat" alt="project views" />
  </a>
  <a href="https://github.com/yusufacik26/AI-Mini-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/yusufacik26/AI-Mini-Bot?style=flat&color=yellow" alt="Stars" />
  </a>
  <img src="https://img.shields.io/badge/Python-3.13%2B-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/AI-Gemini_2.5_Flash-orange?logo=google&logoColor=white" />
</p>

---

## 🧠 About The Project

🎓 **AI Mini Bot** is an intelligent, physical desktop assistant built using:
- 🐍 **Python** | 💻 **Windows OS API**
- 🤖 **Google Gemini 2.5 Flash** (GenAI SDK) & **Edge-TTS**
- 👁️ **Computer Vision** & **Hardware Integration (ESP32)**

🧪 This project bridges the gap between hardware and intelligent software, bringing the AI buddy concept to the Windows ecosystem. It strips away complex servo dependencies to achieve a pure, stable, and highly responsive AI assistant experience.  
🚀 It sees, hears, speaks, and interacts with your PC.

---

## 🌟 Key Features

🔹 **Natural Voice Interaction**  
*Listens via microphone and speaks fluently in Turkish using Edge-TTS (AhmetNeural).*  
`SpeechRecognition` • `Edge-TTS` • `Pygame`

🔹 **Visual Perception (Vision)**  
*Sees its environment through the ESP32 camera, allowing Gemini to analyze objects, faces, and context.*  
`ESP32-CAM` • `Gemini Vision`

🔹 **Dynamic OLED Expressions**  
*Changes facial expressions (happy, sad, thinking, etc.) on an SSD1306 OLED screen based on its current emotion.*  
`I2C` • `HTTP Requests`

🔹 **Persistent Memory & PC Integration**  
*Remembers past conversations and executes Windows tasks (web search, save notes, open apps).*  
`Vectorless Memory` • `OS Subprocess`

---

## 🛠️ Tech Stack

**Core Engine:**  
`Python 3.13` • `Google GenAI SDK` • `Asyncio`

**Hardware (The Body):**  
`ESP32` (e.g., Seeed XIAO ESP32S3 Sense) • `SSD1306 OLED (128x64)`

**Audio & Vision:**  
`SpeechRecognition` • `Edge-TTS` • `Pillow (PIL)`

---

## 🚀 Installation & Setup

### 1. Hardware (ESP32)
- Flash the `bot_face.ino` code to your ESP32.
- Update the **SSID** and **Password** inside the code to match your Wi-Fi network.
- Note the IP address from the Serial Monitor (115200 baud).

### 2. Software (Python)
Run the following command to install required dependencies:
```bash
pip install google-genai edge-tts SpeechRecognition pygame httpx Pillow
