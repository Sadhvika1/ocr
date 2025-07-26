# 🎧 Audio Narration of Text & Graphics

A smart and accessible tool that converts **text and graphics into audio narration**. Designed with inclusivity in mind, this app helps visually impaired users and language learners interact with visual content through spoken output.

> Built using **Streamlit, EasyOCR, Google Translate, and gTTS**.

---

## ✨ Features

- 📝 Extracts and reads text from uploaded images (OCR)
- 🌐 Translates extracted text into multiple languages
- 🔊 Converts text into spoken audio using Google Text-to-Speech
- 🎨 Sleek dark-themed UI using Streamlit custom styles
- 📸 Supports narration of multilingual images (e.g., English & Hindi)

---

## 🛠️ Tech Stack

- **Frontend & UI**: Streamlit
- **Backend Libraries**:
  - `easyocr` – OCR for image text detection
  - `googletrans` – Language translation
  - `gTTS` – Text-to-speech audio
  - `langdetect` – Language auto-detection
  - `Pillow`, `NumPy` – Image handling and processing

---

## 📂 Project Structure

Audio-Narration-of-Text-Graphics/
├── project.py # Main Streamlit app
├── images/ # Sample images for testing (optional)
├── requirements.txt # Python dependencies
├── README.md # This file
├── *.jpg / *.png # Sample assets

## 🧑‍💻 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/audio-narration.git
   cd audio-narration
