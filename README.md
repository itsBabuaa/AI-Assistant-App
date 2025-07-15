# **V AI – Anime-Style Desktop Voice Assistant**


**V AI** is a **desktop-based virtual assistant** with an anime-style GUI.
It responds to **voice or text commands**, opens websites, searches the web, explains topics, plays Spotify music, sets timers, and even has smart small-talk responses powered by **Google Gemini AI**.

---

## ✨ **Features**

✅ **Voice Recognition** – Speak naturally using your microphone
✅ **Natural Voice Replies** – Microsoft Edge TTS with Jenny Neural voice
✅ **Smart Fallback Replies** – Powered by **Google Gemini AI**
✅ **Search & Answer** – Google, YouTube, ChatGPT, or Wikipedia
✅ **Timers & Reminders** – “Set a timer for 5 minutes”
✅ **Open/Close Apps & Websites** – “Open YouTube” or “Close Chrome”
✅ **Spotify Music Control** – Play songs directly on Spotify
✅ **Animated GUI** – Anime-style GIF background with Tkinter
✅ **Small Talk Responses** – Friendly interactions

---

## 🖥 **Tech Stack**

* **Python 3.9+**
* **Tkinter + Pillow** → GUI with animated GIF
* **SpeechRecognition** → Converts voice to text
* **edge-tts + playsound** → Text-to-speech replies
* **Wikipedia API** → Quick topic summaries
* **Google Gemini API** → Smart AI fallback replies
* **pygetwindow + pyautogui** → Controls windows & Spotify

---

## 📦 **Installation**

### 1️⃣ Clone this repo

```bash
git clone https://github.com/itsBabuaa/AI-Assistant-App.git
cd v-ai
```

### 2️⃣ Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 **Setup API Key**

This assistant uses **Google Gemini AI** for fallback answers.

1. Get your **Google API Key** from [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Create a `.env` file in the project folder:

```
GOOGLE_API_KEY=your_google_api_key_here
```

---

## ▶️ **Run the Assistant**

```bash
python main.py
```

It will:
✅ Show an anime-style GUI
✅ Greet you based on the time of day
✅ Let you type or press **F2** to speak

---

## 🗂 **Commands You Can Try**

* **“Open YouTube / Google / Spotify”** → Opens website
* **“Search for cute cats on YouTube”** → Searches YouTube
* **“Tell me about Python programming”** → Wikipedia summary
* **“What do you mean by AI?”** → Explains meaning
* **“Set a timer for 2 minutes”** → Alerts when done
* **“Play Despacito on Spotify”** → Plays song
* **“Who is Elon Musk?”** → Wikipedia answer
* **“Repeat after me hello world”** → Repeats your text
* **“Exit”** → Closes the assistant

---

## 🤖 **How It Works**

1. Listens for voice or reads text from the GUI
2. Checks if it’s a known command → open website, search, timer, etc.
3. If not recognized → Sends it to **Gemini AI** for a smart short reply
4. Speaks the response using **edge-tts**

---

## 📌 **Future Improvements**

* ✅ Add memory for previous chats
* ✅ Custom voice selection
* ✅ More natural small-talk responses
* ✅ Multi-language support

---

## 🏆 **Credits**

* **Google Gemini AI** – for smart replies
* **Microsoft Edge TTS** – for natural-sounding voice
* **Wikipedia API** – for quick info

---

## ❤️ **Contributing**

Pull requests are welcome!
If you have ideas, open an issue or fork and improve it.

---

## 📜 **License**

MIT License – free to use & modify.

✅ **Add badges (Python version, License, etc.)**
✅ **Include a ready-made `.env.example`**
✅ Or generate **sample screenshots/GIF placeholders** for the repo?

What should I include next?
