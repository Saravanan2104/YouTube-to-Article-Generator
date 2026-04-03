# 🎥 YouTube to Article Generator (AI Powered)

Transform any YouTube video into a **professional, Medium-style article website** using AI.

This project extracts YouTube transcripts and converts them into structured, engaging articles — then automatically generates a **fully responsive frontend webpage**.

---

## ✨ Features

- 🎬 Extracts transcript from YouTube videos
- ✍️ Converts raw transcript → **professional article**
- 🧠 Uses AI for:
  - Content summarization
  - Structured writing
  - Recursive summarization for long videos
- 🌐 Generates **production-ready website**
  - HTML, CSS, JS
- 📱 Fully responsive (mobile-first)
- 🌙 Dark / Light theme toggle
- ⚡ Clean Medium/Dev.to style UI
- 📦 Outputs downloadable ZIP file

---

## 🧠 How It Works

1. **Input YouTube URL**
2. Extract transcript using LangChain loader
3. AI processes transcript:
   - Removes noise (intro, ads, promotions)
   - Focuses only on technical content
4. Converts into structured article:
   - Headings
   - Code snippets
   - Actionable steps
5. Generates frontend:
   - `index.html`
   - `style.css`
   - `script.js`
6. Packages everything into a ZIP file

---

## 🛠️ Tech Stack

- Python
- LangChain
- Gemini (Google GenAI)
- YouTube Loader
- HTML5, CSS3, JavaScript

---

## 📂 Project Structure
├── app.py
└── README.md


---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/youtube-article-generator.git
cd youtube-article-generator

pip install -r requirements.txt

3. Add API Key

Create .env file:

gemini_key=YOUR_GOOGLE_API_KEY
4. Run the project
python main.py
📥 Example Input
https://youtu.be/KdEDSMJnPJE
📤 Output
✍️ AI-generated article
🌐 Website files:
index.html
style.css
script.js
📦 website.zip
