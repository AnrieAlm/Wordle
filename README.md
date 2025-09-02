# 🎮 Multilingual Wordle (Java)

A **console-based Wordle clone in Java** with support for **English, French, and Portuguese**.  
Players must guess a 5-letter word within 6 attempts, with helpful color-coded feedback.  

---

## ✨ Features

- 🌍 **Multilingual Support**: English, French, Portuguese  
- 🎨 **Color Feedback** (ANSI escape codes):
  - 🟩 **Green** → Correct letter in the correct position  
  - 🟨 **Yellow (\*)** → Correct letter in the wrong position  
  - ⬜ **Gray** → Letter not in the word  
- 📜 **Game Rules** displayed in chosen language  
- 🕹️ **Menu Options**:
  - Quit the game  
  - View rules again  
  - Restart the current game  
  - Play a new game  
- ❌ **Input validation**: only accepts 5-letter words, no numbers or symbols  
- 🔀 **Random word generation** from language-specific word banks  

---

## 🖼️ Demo (Console)

### Game Start
*************************************************************************************
██╗    ██╗ ██████╗ ██████╗ ██████╗ ██╗     ███████╗
██║    ██║██╔═══██╗██╔══██╗██╔══██╗██║     ██╔════╝
██║ █╗ ██║██║   ██║██████╔╝██╔══██╗██║     █████╗  
██║███╗██║██║   ██║██╔══██╗██║  ██║██║     ██╔══╝  
╚███╔███╔╝╚██████╔╝██║  ██║██████╔╝███████╗███████╗
 ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚═════╝ ╚══════╝╚══════╝
*************************************************************************************
Welcome to Wordle!
Your mission: Guess the 5-letter word in 6 tries or fewer.


### Screenshots

- **Welcome Screen**  
  ![Welcome Screen](https://github.com/AnrieAlm/Wordle/blob/main/WelcomeScreen.png)

- **Select Language**  
  ![Select Language](https://github.com/AnrieAlm/Wordle/blob/main/WelcomeScreen.png)

- **Gameplay**  
  ![Gameplay](https://github.com/AnrieAlm/Wordle/blob/main/GamePlay.png)

### Example Guess

Attempt 1/6. Enter a 5-letter word:
Feedback: _  *  _  _  *

(🟩 = Green / 🟨 = Yellow / ⬜ = Gray)

# 1. 🚀 How to Run

Clone the repository: git clone https://github.com/Anriel-Alm/Wordle.git
cd Wordle

Compile the Java program:

javac griffith/Wordle.java


Run the game:

java griffith.Wordle

# 2.📂 Project Structure
multilingual-wordle/
│
├── griffith/
│   └── Wordle.java    # Main game logic
│
├── docs/              # Screenshots folder
│   ├── start.png
│   ├── feedback.png
│   └── win.png
│
└── README.md          # Documentation

# 3.📝 Rules

Guess a valid 5-letter word.

No repeating letters allowed.

After each guess:

🟩 Green → correct letter in correct spot

🟨 Yellow → correct letter, wrong spot

⬜ Gray → letter not in word

You have 6 attempts to find the word.

# 4.🌐 Languages

🇬🇧 English (WORD_BANK_ENGLISH)

🇫🇷 French (WORD_BANK_FRENCH)

🇵🇹 Portuguese (WORD_BANK_PORTUGUESE)

🛠️ Requirements -Java 8 or higher

Console/terminal with ANSI color support

# 5.📌 Future Improvements

Add larger word banks

Support custom word input for multiplayer mode

Track high scores / stats across games

# 6.👤 Author

Anriel Mariel Almeida
📌 Student ID: 3168178
