# 📊 WhatsApp Chat Analyzer

A **Streamlit-powered** web app that provides insightful analytics and visualizations on your exported WhatsApp chats. Whether you're curious about your chatting habits or exploring NLP and data analysis—this tool brings your conversations to life!

https://whatsapp-chat-analyzer-roomil.streamlit.app/

---

## 📌 Features

- ✅ Upload your `_chat.txt` file directly
- 📈 Get top-level stats (messages, words, media, links)
- 🧍 See individual or group-level message activity
- 📅 Daily & Monthly message timelines
- 📆 Active day/month and heatmap of weekly activity
- 💬 Most used words (with WordCloud)
- 😊 Emoji usage statistics
- 🔗 Shared link extraction

---

## 🛠️ Built With

- **Python 3**
- [Streamlit](https://streamlit.io/) - For building the interactive UI
- **Pandas** - For data manipulation
- **Matplotlib & Seaborn** - For plotting
- **WordCloud** - For generating word clouds
- **emoji & urlextract** - For emoji and link analysis

---

## 🚀 How to Run the App Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Streamlit App

```bash
streamlit run whatsapp_app.py
```

---

## 📂 File Structure

```
├── whatsapp_app.py        # Main Streamlit app
├── preprocessor.py        # Chat data cleaning & parsing
├── support.py             # All analytical functions
├── _chat.txt              # (Sample WhatsApp chat file)
├── requirements.txt       # Python dependencies
├── README.md              # You're reading this!
```

---

## 📁 Exporting WhatsApp Chat

1. Open WhatsApp → Tap on any chat
2. Tap on `⋮` > `More` > `Export Chat`
3. Select **Without Media** or **Include Media**
4. Transfer the `_chat.txt` file to your system


---

## ⭐️ Give it a Star!

If you find this project useful, consider giving it a ⭐️ on GitHub — it helps others discover it too!
