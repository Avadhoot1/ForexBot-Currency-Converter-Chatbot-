# 💱 ForexBot – Currency Converter Chatbot

An interactive chatbot for **real-time currency conversion** built using **Dialogflow**, **Python**, and **CurrencyConverterAPI**.  
The bot processes natural language queries (e.g., *“Convert 100 USD to INR”*) and responds with live exchange rates.  
Local deployment and testing are supported using **Ngrok**.  

---

## 🚀 Features
- 🌍 Real-time multi-currency conversion  
- 🗣️ Natural language understanding with **Dialogflow**  
- 🔑 Live exchange rates via **CurrencyConverterAPI**  
- 🐍 Backend logic in **Python**  
- 🔗 Local deployment & tunneling using **Ngrok**  

---

## 🛠️ Tech Stack
- **Python** – Backend processing  
- **Dialogflow** – NLP and intent recognition  
- **CurrencyConverterAPI** – Live forex data  
- **Ngrok** – Local server tunneling  

---

## 📂 Project Structure

ForexBot-Currency-Converter-Chatbot/

│── forexbot.py # Backend logic

│── dialogflow_intent.json # Exported intents

│── requirements.txt # Dependencies

│── ngrok_setup.md # Ngrok setup guide

│── docs/ # Screenshots or demo files

**Create a virtual environment (optional)**

python -m venv venv

source venv/bin/activate   # On Linux/Mac

venv\Scripts\activate      # On Windows

**Install dependencies**

pip install -r requirements.txt

**Configure Ngrok**

Download Ngrok from https://ngrok.com
.

Run:ngrok http 5000


**Set up API key**

Get a free key from CurrencyConverterAPI
.

Save it in config/config.json (example: config_example.json).

**Run the backend**

python forexbot.py

---


## 🤖 How It Works

1. User asks: “Convert 250 EUR to GBP”.

2. Dialogflow identifies intent, extracts amount & currencies.

3. Python backend fetches live rates from CurrencyConverterAPI.

4. The chatbot replies with the converted value.

---

## 👤 Author

Avadhoot Wamane

📧 Email - avadhootwamane461@gmail.com 
 | 🌐 LinkedIn - https://www.linkedin.com/in/avadhoot-wamane/
