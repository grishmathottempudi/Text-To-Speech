# 🔊 Text-to-Speech Converter

A simple Text-to-Speech (TTS) web application built using **Python**, **gTTS (Google Text-to-Speech)**, and **Gradio**. The application converts user-entered text into speech and returns an audio file that can be played directly in the browser.

---

## Features

- 📝 Convert text into natural-sounding speech
- 🎙️ Uses Google's Text-to-Speech (gTTS) engine
- 🌐 Simple and interactive Gradio web interface
- 🔊 Generates downloadable MP3 audio output
- ⚡ Fast and lightweight application

---

## Technologies Used

- Python
- Gradio
- gTTS (Google Text-to-Speech)
- Click
- Typer

---

## Project Structure

```
Text-to-Speech-Converter/
│
├── app.py
├── requirements.txt
├── README.md
└── output.mp3 (generated after execution)
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Text-to-Speech-Converter.git
cd Text-to-Speech-Converter
```

### 2. Install the required packages

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
python app.py
```

Gradio will generate a local URL similar to:

```
http://127.0.0.1:7860
```

Open the link in your browser.

---

## How to Use

1. Enter the text you want to convert into speech.
2. Click **Submit**.
3. The application generates an MP3 audio file.
4. Play or download the generated speech directly from the interface.

---

## Example Input

```
Hello! Welcome to the Text-to-Speech Converter application.
```

---

## Example Output

- 🎧 Audio file (`output.mp3`) containing the spoken version of the input text.

---

## Future Improvements

- Support multiple languages
- Voice selection (male/female)
- Adjustable speech speed
- Save audio with custom filenames
- Batch text-to-speech conversion
- Upload text files for conversion

---

## Author

**Grishma Thottempudi**

B.Tech – Data Science

---

## License

This project is developed for educational and learning purposes.
