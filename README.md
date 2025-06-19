# 🧠 MediBot – AI Symptom Checker Chatbot

MediBot is an AI-powered chatbot that helps users identify potential health issues based on symptoms and provides a list of nearby hospitals using a static dataset.

## 🚀 Features

- 🤖 Intent classification using a custom-trained PyTorch model
- 💬 Web-based chat interface with Flask
- 📍 Location-based hospital lookup (based on area names like "Kilpauk", "Adyar")
- 📁 Static dataset – works offline, no external API needed
- 🧪 Terminal-based testing version for debugging

---

## 🏗️ Project Structure

```
symptom-checker-chatbot/
├── data/
│   ├── intents.json
│   └── medical_centers.json
│
├── model/
│   ├── model.py
│   ├── train.py
│   └── model.pth
│
├── static/
│   └── style.css
├── templates/
│   └── index.html
├── app.py
├── predict.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/symptom-checker-chatbot.git
cd symptom-checker-chatbot
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. (Optional) Retrain the model:
```bash
python model/train.py
```

4. Run the Flask app:
```bash
python app.py
```

Then visit `http://localhost:5000` in your browser.





