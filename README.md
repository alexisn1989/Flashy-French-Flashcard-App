🗂️ Flashy — French Flashcard App
A beautiful and fully functional French language learning flashcard
app built with Python, Tkinter and Pandas that tracks your progress
automatically.
📋 About
Flashy helps you learn French vocabulary using the spaced repetition
technique. Flash cards automatically flip from French to English after
3 seconds. Mark words you know and they're removed from your deck
forever. Your progress is saved automatically so you pick up exactly
where you left off!
✨ Features

🇫🇷 French to English flashcards
⏱️ Auto flips to English after 3 seconds
✅ Mark words you know to remove them
💾 Progress saved automatically to CSV
🔄 Picks up where you left off
🎨 Beautiful green card UI

🖥️ Screenshot
<img width="936" height="797" alt="french" src="https://github.com/user-attachments/assets/d05ebd5e-d1f0-42e7-8119-092371be0320" />
t
<img width="914" height="777" alt="english" src="https://github.com/user-attachments/assets/d3a3deb5-1b03-4357-a371-132ebbd45dfd" />
here]
🎮 How to Use

Run the program
French word appears on card
Try to remember the English translation
Card automatically flips to English after 3 seconds
Click ✅ if you knew it — word removed from deck
Click ❌ if you didn't — word stays in deck
Keep going until you know all words!

🛠️ Built With

Python 3
Tkinter — GUI framework
Pandas — CSV data handling
Random module — card selection

🚀 How to Run

Make sure Python is installed
Install Pandas:

pip install pandas

Clone this repository:

git clone https://github.com/alexisn1989/flashy-flashcard-app

Run the program:

python main.py
📁 Project Structure
flashy-flashcard-app/
├── main.py                    ← main program
├── data/
│   ├── french_words.csv       ← original word list
│   └── words_to_learn.csv     ← generated progress file
└── images/
    ├── card_front.png         ← front card image
    ├── card_back.png          ← back card image
    ├── right.png              ← correct button
    └── wrong.png              ← wrong button
📦 Requirements
pandas
tkinter (built into Python)
💡 What I Learned

Building GUI applications with Tkinter
Canvas widget for custom graphics
Timer management with after() and after_cancel()
Exception handling with try/except/else
Reading and writing CSV files with Pandas
Saving and loading user progress
Random selection from lists
Dynamic UI updates

👨‍💻 Author
Alexi — Aspiring Python Developer
Currently completing Angela Yu's 100 Days of Code bootcamp
📍 Virginia Beach, VA | Open to remote opportunities
🔗 LinkedIn: your-linkedin-url
🐙 GitHub: github.com/alexisn1989
