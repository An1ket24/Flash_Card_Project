 🧠 Flash Card Language Learning App

A simple flashcard app built with Python and Tkinter to help you learn the most frequently used words in a foreign language — starting with French 🇫🇷 → English 🇬🇧.

The app uses real subtitle-based word frequency data, displays one word at a time, flips the card after a few seconds, and allows you to track what you've learned.

 🚀 Features

- 🃏 Interactive flashcard GUI using Tkinter
- 🔁 Card flips automatically after 3 seconds
- ✅ Track known vs unknown words
- 📂 Saves progress to a CSV file (`words_to_learn.csv`)
- 📊 Uses real frequency word list (`french_words.csv`)
- 🔒 Packaged as `.exe` for easy sharing (no Python required)

📁 Project Structure

FlashCardApp/
├── main.py # Main application script
├── data/
│ ├── french_words.csv # Original word list
│ └── words_to_learn.csv # Auto-generated progress file
├── images/
│ ├── card_front.png
│ ├── card_back.png
│ └── right.png / wrong.png
├── dist/
│ └── main.exe # (Optional) Compiled executable
└── README.md


 🖥️ How to Run
1. Clone or download the repo
2. Install dependencies:
   ```bash
   pip install pandas

💾 Data Source
Word frequency list by HermitDave on GitHub
Translations done using Google Sheets Translate function
