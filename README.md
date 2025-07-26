# 🧠 Desktop Assistant using Python (Jarvis)

A smart, multilingual desktop assistant built with Python that can operate both via a **web interface** and **command line**, providing voice-driven interaction, real-time query resolution, and automation capabilities—like your very own Jarvis!

---

## 🚀 Features

### 🔊 **1. JARVIS-style Voice Assistant (Command-Line)**

* Voice-controlled command-line interface.
* Greets user based on time of day.
* Performs tasks such as:

  * Search on **Wikipedia**.
  * Open websites: **YouTube**, **Google**, **GitHub**, etc.
  * Tell the **current time**.
  * Give **spoken responses** using `pyttsx3` (text-to-speech).

### 🌐 **2. Multilingual AI Assistant (Web App)**

* Built with **Streamlit** for easy interaction.
* Accepts **voice input** from users.
* Supports **multiple languages**.
* Answers queries using advanced **language models**.
* Converts responses to **speech** and allows downloading the audio file.

---

## 📦 Tech Stack

* **Python 3.10**
* **SpeechRecognition**, **pyttsx3**, **wikipedia**, **datetime**
* **Streamlit** for the web interface
* **Google Text-to-Speech (gTTS)** for audio generation
* **OpenAI or NLP API** (optional for smarter responses)
* **Virtual Environment** via Conda

---

## 🛠️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ankit-kumarz/Desktop-Assistant-using-Python.git
cd Desktop-Assistant-using-Python
```

### 2. Create and Activate Virtual Environment

```bash
conda create -n assistant python=3.10
conda activate assistant
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Web App (Streamlit)

```bash
streamlit run app.py
```

### 5. Run the CLI Voice Assistant

```bash
python jarvis.py
```

---

## 📁 Project Structure

```
├── app.py                 # Streamlit Web App
├── jarvis.py              # Command-line Voice Assistant
├── requirements.txt       # Python dependencies
├── static/                # Audio file output
└── README.md              # Project README
```

---

## ✅ Git Commands for Contribution

```bash
git add .
git commit -m "Add feature/fix"
git push origin main
```

---

## 📸 Screenshots

<details>
<summary>🖼 Click to expand</summary>

> You can add images of the UI or command-line demo here
> Example:
> ![Jarvis Web App](static/demo-ui.png)
> ![Jarvis CLI](static/demo-cli.png)

</details>

---

## 💡 Future Improvements

* Add personal productivity features: email reading, weather updates, task reminders.
* Integrate with **LLMs (like GPT)** for more intelligent conversations.
* Improve multilingual support using translation APIs.
* Deploy Streamlit app with **Streamlit Cloud or Hugging Face Spaces**.

---

## 📬 Contact

**👨‍💻 Ankit Kumar**
📧 Email: [ankitrajj1068@gmail.com](mailto:ankitrajj1068@gmail.com)
🌐 GitHub: [@ankit-kumarz](https://github.com/ankit-kumarz)

---

## ⭐ Show Your Support

If you liked this project, consider giving it a ⭐ on GitHub.
Pull requests and suggestions are welcome!

---


