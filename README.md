# 🤖 Friday - Your Personal Voice Assistant (React App)

Friday is a smart, voice-controlled AI assistant built using **ReactJS** and the **Web Speech API**. It can understand your voice commands, respond with voice, and take actions like opening websites or giving information from Wikipedia or Google.

![Friday AI](./src/ai-human.avif)

---

## 🚀 Features

- 🎙️ **Voice Recognition** (Speech-to-Text)
- 🔊 **Voice Response** (Text-to-Speech)
- 🌐 **Open Websites** via voice (e.g., "open YouTube")
- 🤝 **Custom Responses** for specific questions (e.g., "What is your name?")
- 🧠 **Wikipedia Integration** for famous personalities
- 🔍 **Google Search** fallback for unknown queries
- 👨‍💻 Built entirely in **ReactJS**

---

## 📸 Demo

> ((https://fridaybyanuj.vercel.app/))

---

## 🛠️ Technologies Used

- **ReactJS**
- **JavaScript (ES6+)**
- **Web Speech API**  
  - `SpeechRecognition` for listening  
  - `SpeechSynthesis` for speaking
- **Wikipedia API** for fetching person summaries
- **Google Search** fallback

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/anujgaurave/friday-voice-assistant.git
   cd friday-voice-assistant
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. Open your browser and visit `http://localhost:5173`

---

## 🧑‍💻 How to Use

- Click the **Start Listening** button
- Say commands like:
  - `"Open YouTube"` – opens YouTube in a new tab
  - `"What is your name?"` – gets a custom reply from Friday
  - `"Tell me about Elon Musk"` – fetches summary from Wikipedia
  - `"Who is Lovely?"` – returns a fun custom response

---

## 📂 Project Structure

```bash
src/
├── App.jsx
├── ai-human.avif       # Image for UI
└── index.css            # Styling (optional)
```

---

## 📌 Voice Commands Supported

| Command Example            | Action Description                          |
|---------------------------|----------------------------------------------|
| `Open YouTube`            | Opens YouTube in new tab                    |
| `What is your name?`      | Replies with assistant's name               |
| `Hello Friday`            | Greets you back                             |
| `Tell me about Elon Musk` | Fetches and reads a short Wikipedia bio     |
| `What is your age?`       | Returns Friday's age                        |
| `Who is Lovely?`          | Easter egg custom reply                     |
| Any other query           | Opens Google search for that phrase         |

---


## 🧠 Upcoming Features (Ideas 💡)

- Add chatbot-like response history
- UI improvements (Dark Mode, Animations)
- Add support for Hindi or other languages
- Add command to read news or weather

---

## 🙌 Acknowledgements

- Voice APIs from Web Speech API  
- Wikipedia API for knowledge base  
- Google for fallback searches

---

## ✨ Author

**Anuj Gaurave**  
👨‍🎓 B.Tech Student, Jaipur Engineering College  
📫 [LinkedIn](https://www.linkedin.com/in/anujgaurave) | [Instagram](https://www.instagram.com/anujgaurave)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

### 💬 If you like this project, please give it a ⭐ on GitHub and feel free to contribute!
