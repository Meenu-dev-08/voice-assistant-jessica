# 🎙️ Jessica AI Voice Assistant

🕹️ Overview:-

Jessica is a Python-based **AI Voice Assistant** built to simplify your daily tasks through natural voice interactions. It listens to your commands and performs actions like searching the web, playing music, giving news updates, capturing screenshots, sending emails, setting alarms, and much more — all hands-free.

This project is a comprehensive implementation of voice-based automation, combining **Natural Language Processing**, **Speech Recognition**, **Text-to-Speech**, **System Automation**, and **API integration** into one intelligent assistant.


## 🧠 Why Jessica?

In today’s fast-paced digital environment, multitasking and productivity are essential. Jessica is developed to function as a personal digital assistant that:
- Responds to your **voice commands**
- **Automates** routine desktop tasks
- Provides **real-time information**
- Enhances **accessibility** for users with physical limitations
- Serves as a **learning platform** to explore Python, AI, and system automation

---

## 🚀 Key Highlights :-

- Works completely through **voice interface**

- Can understand **English commands** (with Indian accent support)

- Offers **modular, expandable architecture** — new features can be easily added

- Completely runs on **open-source Python libraries**

- All tasks are executed in real-time, making it ideal for productivity

---

## 🧩 Features Breakdown :-

| Feature                     | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| Wikipedia Search           | Fetches and reads summaries from Wikipedia                                  |
| Web Browsing               | Opens Google, YouTube, or any website via voice                             |
| Local Music Player         | Plays songs from the designated folder                                      |
| Time & Date Reporter       | Tells you the current system time and date                                  |
| Screenshot Tool            | Captures and saves a screenshot with a timestamp                           |
| System Control             | Shutdown, restart, or lock your system via voice command                    |
| File Search & Open         | Finds and opens files from your computer                                   |
| YouTube Player             | Searches and plays any video on YouTube using `pywhatkit`                   |
| Joke Generator             | Tells programming jokes for fun                                             |
| Alarm & Reminder           | Sets an alarm based on time you mention                                     |
| News Headlines             | Fetches live headlines using NewsAPI                                       |
| Calculator                 | Evaluates math expressions through voice                                    |
| Quote of the Day           | Reads motivational quotes via Quotable API                                 |
| WhatsApp Message Sender    | Sends messages via WhatsApp (scheduled)                                     |
| Webcam Capture             | Takes photo using system’s webcam                                           |
| Weather Reporter           | Provides temperature & condition of any city                               |
| Battery & System Info      | Gives system battery status and CPU info                                    |
| Email Sender               | Sends email via SMTP after taking recipient, subject, and body              |


## 📸 Screenshots :-

 ▶️ Jessica Terminal Startup & Command Execution
 <img src="screenshots/screenshot_20250417_210431.png" alt="Jessica Running Screenshot" width="800">

 📁 File Search & Voice Response
 <img src="screenshots/screenshot_20250423_110215.png" alt="File Search Screenshot" width="800">

 🕒 Telling Time and Date
  <img src="screenshots/screenshot_20250428_200251.png" alt="Time Command Screenshot" width="800">

 🧠 Imports and Module Setup
  <img src="screenshots/screenshot_20250429_115558.png" alt="Import Screenshot" width="800">

---

  ## 🛠️ Tech Stack :-

  **Language:** Python 3.x
  
  **Libraries:**  
  
  - `speech_recognition` – for converting voice to text  
  
  - `pyttsx3` – for voice response  
  
  - `pyautogui` – for automation like taking screenshots  
  
  - `pyjokes` – for telling jokes  
  
  - `pywhatkit` – for WhatsApp messaging & YouTube control  
  
  - `cv2` – for camera access  
  
  - `requests` – for API integration  
  
  - `psutil` – for system & battery info  
  
  - `smtplib` – for sending emails
    
   ---
   
   **APIs:-**
  
  - OpenWeatherMap API  
  - NewsAPI  
  - Quotable.io (Quotes of the day)
    
---

**📌 Install dependencies:-**

pip install -r requirements.txt

---

## Create a .env file or directly paste your API keys in your script:-

NewsAPI: https://newsapi.org

OpenWeatherMap: https://openweathermap.org/api

---

**🔋 Run the script**:-

python jessica_ai.py

---

📝 **Requirements**:-
     
     Python 3.x

     Microphone

    (Optional) Webcam

     Internet for news/weather APIs
---

📂 **Folder Structure**:-

├── jessica_ai.py          # Main script

├── mic_test.py            # To check microphone input

├── test.py                # Optional testing scripts

├── screenshots/           # Demo screenshots for README

├── requirements.txt       # List of dependencies

└── README.md

---

✨ **Future Enhancements** :-

  Wake word integration (e.g., “Hey Jessica”)

  GUI interface

  Contextual chatbot mode using GPT API

  Integration with home automation (IoT)

  Portable Android App using Kivy

  ---
  
## 👩‍💻 **Author**

**Meenu Sharma**

*Python Enthusiast | CSE | AI Voice Assistant Developer*

💻 Passionate about building intelligent systems that make everyday tasks easier with automation and voice control.

#Python #VoiceAssistant #AIProject #ArtificialIntelligence #JessicaAI #DesktopAutomation #MachineLearning #SpeechRecognition NaturalLanguageProcessing





