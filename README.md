# Morse Code Translator (Java GUI)

This is a simple Java-based GUI application that translates regular text into Morse code and plays the corresponding Morse tones.

## 💡 Features
- Converts English letters, numbers, and symbols to Morse code
- GUI built with Java Swing
- Real-time conversion as you type
- Audio playback of Morse code using beeps

## 📦 Tech Stack
- Java (JDK 8+)
- Java Swing for GUI
- Java Sound API for audio

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project in any Java IDE (like IntelliJ IDEA or Eclipse).
3. Compile and run the `App.java` file.
4. A GUI window will open. Type your message, and press `Play Sound` to hear the Morse code.

## 🧠 Components

- `App.java`: Launches the GUI
- `MorseCodeTranslatorGUI.java`: Handles UI components and user interactions
- `MorseCodeController.java`: Converts text to Morse and handles audio generation
- `Main.java`: Sample demo file (not connected to GUI)

## 🔊 Morse Playback Notes
- Dot (.) = short beep  
- Dash (-) = long beep  
- Slash (/) = space between words  

## 📄 License
This project is open-source and free to use for educational purposes.
