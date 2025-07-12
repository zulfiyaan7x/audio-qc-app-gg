<h1 align="center">🎧 Audio QC Automation App</h1>
<p align="center">
  <i>One-click mastering quality checker for FLAC/WAV files – built with ❤️ using Python & Streamlit</i>
</p>

---

## 🧠 What is this?

**Audio QC App** is a full-featured automation toolkit designed for audio engineers, record labels, and production houses to:

- ✅ Scan audio for mastering issues
- 🔧 Automatically fix problems (fade, gain, silence, DC offset, etc.)
- 📊 Generate reports and pass/fail verdicts
- 💡 Get AI-based QC explanations *(Pro Feature)*

---

## 🚀 Key Features

- 🎚️ **LUFS / True Peak / DC Offset / Silence Check**
- 🔁 Auto Fade In/Out, Trim Silence, Gain Match
- 📈 Zoomable Waveform & Audio Playback
- 📄 Exportable **PDF Report** and **CSV Fix Summary**
- 🔄 Bangla-English UI Toggle
- 🧠 GPT-style AI feedback *(optional addon)*
- ✅ OFFSTEP 100% QC Approval Compatible

---

## 🗂 Folder Structure

```bash
Zulfiyaan/
├── app.py                # Streamlit main app
├── requirements.txt
├── .streamlit/           # App config
├── assets/               # Icons, waveforms
├── data/                 # Uploaded user audio
├── export/               # Final approved exports
├── fixes/                # Auto-fixed audio
├── history/              # QC sessions
├── logs/                 # Activity logs
├── reports/              # PDF reports
└── scripts/              # Backend engines
    ├── audio_analyzer.py
    ├── fix_engine.py
    └── qc_reporter.py
```

---

## ⚙️ How to Run (Termux / Linux / Desktop)

```bash
# Step 1: Clone the repo
git clone https://github.com/zulfiyaan7x/audio-qc-app-gg.git
cd audio-qc-app-gg

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the app
streamlit run app.py
```

---

## 🌍 Language Support

- 🇧🇩 Bangla (বাংলা UI Toggle)
- 🇺🇸 English (Default)

Switch using the top-right toggle in the UI.

---

## 📸 Screenshots

| Dashboard | Fix Report | Waveform |
|-----------|------------|----------|
| ![](assets/screens/dashboard.png) | ![](assets/screens/report.png) | ![](assets/screens/waveform.png) |

> ⚠️ Screenshots are placeholders – replace with real assets.

---

## 📜 License

MIT License.  
Crafted with love by [@zulfiyaan7x](https://github.com/zulfiyaan7x)

---

## 💬 Feedback or Contributions?

PRs welcome.  
For feature requests, open an [Issue](https://github.com/zulfiyaan7x/audio-qc-app-gg/issues).
