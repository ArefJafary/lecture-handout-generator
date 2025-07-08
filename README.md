# 📘 Lecture Handout Generator (Colab Notebook)

Automatically generate structured, print-ready handouts from lecture **audio** and **board images** using Whisper (ASR) and Gemini Flash 2.5 (LLM).  
Specially designed for **Persian-language lectures**, with support for original terminology and embedded board visuals.

---

## 🚀 Overview

This Colab notebook creates study-ready handouts from:
- 🎤 **Lecture Audio** – transcribed using Whisper ASR  
- 📷 **Board Images** – integrated with labeled figures  
- 🧠 **Gemini Flash 2.5** – turns speech + image into structured notes  
- 📄 **Markdown to PDF** – clean export of the final handout

---

## 📌 Key Features

- Supports **Persian** and other languages
- Automatically removes transcription errors (e.g. duplicated words)
- Includes labeled diagrams from board images
- Outputs ready-to-print **PDF handouts**

---

## 🧰 Technologies Used

- Google Colab (Python)
- [OpenAI Whisper](https://github.com/openai/whisper) — ASR  
- [Google Gemini Flash 2.5](https://aistudio.google.com/) — LLM  
- `re` — Regular expressions for text cleanup  
- `markdown-pdf` — PDF export from Markdown  

---

## 📄 How to Use

1. **Open the notebook in Google Colab**  
2. **Upload**:
   - Your lecture audio file (e.g., `.mp3`, `.wav`)
   - An image of the course board (e.g., whiteboard or slide)
3. **Enter your Gemini API key**  
   Get it for free at: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
4. **Run cells step by step** to:
   - Transcribe the audio
   - Clean up the text
   - Generate the handout
   - Export it to PDF

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [OpenAI Whisper](https://github.com/openai/whisper)  
- [Google Gemini](https://aistudio.google.com/)
