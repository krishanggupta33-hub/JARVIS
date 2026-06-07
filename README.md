readme_content = """<div align="center">
  <h1>🤖 J.A.R.V.I.S. Reactive Core</h1>
  <p><b><i>Remembers you. Knows where you are. Knows what time it is. Talks to you like a person, not a product.</i></b></p>
</div>

<br/>

## 🚀 Overview

**J.A.R.V.I.S. Reactive Core** is a voice-first, hyper-aware desktop AI companion. Moving beyond standard web-based chatbots, this is a fully integrated system agent featuring a custom **Tkinter-based 60FPS physics HUD** that visually reacts to the audio amplitude of your voice in real-time. 

Powered by the lightning-fast **Groq API** (Llama-3.3-70b), it doesn't just converse—it natively executes PC commands, proactively monitors your system telemetry, and maintains persistent memory across sessions.

## ✨ Key Features

* **🎛️ Immersive Reactive HUD:** A custom-built Tkinter interface featuring a 60FPS particle physics engine, audio waveform visualizers, and animated arcs. The particle field compresses, ripples, and glows dynamically based on live microphone input.
* **⚡ Blazing Fast AI & Voice:** Utilizes Groq's API for near-zero latency token streaming, paired with a dedicated asynchronous thread for Microsoft Edge Neural TTS. JARVIS speaks back instantly.
* **💻 Deep OS Integration:** Parses hidden JSON action blocks from the LLM to control your PC. It can open apps, search the web, manipulate the clipboard, take screenshots, manage volume, and terminate system processes.
* **🧠 Persistent Memory:** Saves facts, user preferences, and full conversation histories locally in `jarvis_brain.json`. It remembers what you discussed yesterday.
* **🌍 Contextual Awareness:** Automatically fetches your real-time location and system time. JARVIS greets you differently on a Monday morning vs. a late Friday night.
* **👁️ Vision & Art:** Features OpenCV integration for webcam face detection and Pollinations.ai for instant, on-demand image generation.
* **🚨 Proactive Monitoring:** A background thread constantly monitors your telemetry. JARVIS will verbally warn you if your CPU spikes over 92% or if your battery drops below 20%.

---

## 🛠️ Tech Stack

* **Language:** Python 3
* **UI Framework:** Tkinter (Custom canvas math & rendering)
* **LLM Engine:** Groq API (`llama-3.3-70b-versatile`)
* **Voice / Audio:** Edge-TTS, PyAudio, SpeechRecognition
* **System Control:** PyAutoGUI, Psutil, OpenCV

---

## ⚙️ Installation & Setup

### 1. Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### 2. Clone & Install Dependencies
Clone this repository and install the required packages:
