# 🥗 MacroSnap

**MacroSnap** is an AI-powered nutrition assistant that analyzes meal photos and answers nutrition-related questions using Google Gemini. It estimates calories and macronutrients and can send personalized nutrition summaries to WhatsApp using Twilio.

## ✨ Features

* 🤖 AI-powered nutrition assistant
* 📸 Meal photo analysis
* 🔢 Calorie and macronutrient estimation
* 💬 Conversational nutrition queries
* 📱 WhatsApp summary delivery

## 🛠️ Technologies

* Python
* Streamlit
* Google Gemini API
* Twilio WhatsApp API
* GitHub

## 📂 Project Structure

```text
MacroSnap/
├── app.py
├── prompts.py
├── requirements.txt
├── .gitignore
└── .streamlit/
    └── secrets.toml.example
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Macrosnap.git
cd Macrosnap
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔐 API Keys

Create:

```text
.streamlit/secrets.toml
```

Add your API credentials:

```toml
GEMINI_API_KEY = "your_gemini_api_key"
TWILIO_ACCOUNT_SID = "your_twilio_account_sid"
TWILIO_AUTH_TOKEN = "your_twilio_auth_token"
TWILIO_WHATSAPP_FROM = "whatsapp:+14155238886"
```

**Never upload `secrets.toml` to GitHub.**

## ▶️ Run Locally

```bash
streamlit run app.py
```

The application will open at:

```text
http://localhost:8501
```

## 🚀 Deployment

MacroSnap can be deployed using **Streamlit Community Cloud** by connecting this GitHub repository and selecting:

```text
app.py
```

Configure the required API credentials in Streamlit Cloud's **Secrets** settings.

## 📌 Project Flow

```text
User
 ↓
Streamlit Interface
 ↓
Gemini AI
 ↓
Meal/Nutrition Analysis
 ↓
Calorie & Macro Results
 ↓
WhatsApp Summary
```

## 👨‍💻 Author

**V. Taruneshwar**
