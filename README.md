# 🤖 Jarvis – AI-Powered Desktop Assistant
Jarvis is a smart desktop assistant designed to perform various tasks efficiently using voice commands. Built with a Python backend and a web-based frontend using HTML, CSS, and JavaScript, Jarvis integrates AI-powered responses and automates system operations seamlessly.

🚀 Features
✅ Voice Recognition & Response – Uses SpeechRecognition and Pyttsx3 for interaction.
✅ ChatGPT Integration – Utilizes Hugchat for intelligent command processing.
✅ Application Automation – Opens system applications based on database entries.
✅ Website Navigation – Directly accesses stored website URLs.
✅ Contact Lookup – Retrieves stored phone numbers from the database.
✅ Music & Media Control – Plays songs using Pywhatkit and Playsound.
✅ Wake Word Detection – Implements pvporcupine for activation via voice.
✅ GUI Interface – Interactive frontend built using Eel.

# 🛠 Technologies Used
# 🌐 Frontend
HTML, CSS, JavaScript – For the user interface.
# ⚙️ Backend
Python – Core processing and logic.
Eel – For connecting Python with the web-based UI.

# 📚 Python Libraries Used
Library	Purpose
Hugchat	ChatGPT-based AI response processing
Playsound (v1.2.2)	Playing sound files
pvporcupine	Wake word detection
PyAudio	Audio stream handling
Pyttsx3	Text-to-Speech conversion
Pywhatkit	Playing YouTube videos, sending WhatsApp messages, etc.
SpeechRecognition	Recognizing voice commands
Webbrowser	Opening websites
Time, OS	System operations
Pyautogui	Automating keyboard and mouse actions

# 🗄️ Database Connection
SQLite3 – Stores essential data for seamless operation.
📌 Data Stored in Database
✅ System Applications' Locations – Opens installed applications via commands.
✅ Contact Details – Retrieves phone numbers.
✅ Website URLs – Accesses frequently used websites.

# 🔧 Installation & Setup
1️⃣ Create Virtual Environment
Make sure Python 3.10.7 is installed, then run:
### python -m venv jarvis_env
Activate the virtual environment:
Windows: jarvis_env\Scripts\activate
Linux/macOS: source jarvis_env/bin/activate

2️⃣ Install Dependencies
# pip install -r requirements.txt
3️⃣ Run the Desktop Assistant
python main.py
# 📸 Screenshots
![Screenshot 2025-02-01 194226](https://github.com/user-attachments/assets/6ae45c69-67cd-4ee7-880a-34f47f9f5fe3)
