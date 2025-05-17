# JAIKA-A-FOOD-CHATBOT-using-Twillo-and-IBM-cloud
# JAIKA – A Food Chatbot   
*Built using Twilio and IBM Cloud*

**Jaika** is a smart, AI-powered chatbot designed to take food orders, interact with users, and simulate a real restaurant experience through chat. Integrated with **Twilio** for messaging and **IBM Watson Assistant** on IBM Cloud for conversation logic.

##  Project Overview

Jaika acts like your digital waiter – it chats with customers, suggests dishes, and takes orders using simple conversational AI. This project is designed to improve user engagement and provide a demo of chatbot integration for restaurants or food apps.

##  Technologies & Tools Used

- **IBM Watson Assistant** – for chatbot flow and intent recognition  
- **Twilio API** – for SMS or WhatsApp messaging support  
- **Python** – backend integration (optional if used)  
- **Flask / Node.js** – for webhook server (if applicable)  
- **Ngrok** – to tunnel localhost for testing webhook  
- **IBM Cloud** – for chatbot hosting and API management

##  Key Features

- AI-powered chatbot that handles food-related conversations  
- Suggests menu items and processes orders  
- Can chat via **SMS** or **WhatsApp** using Twilio  
- Deployed on IBM Cloud for easy access and scalability  
- Easily customizable for different cuisines or restaurants

## How It Works

1. **User** sends a message like “I want to order pizza.”  
2. **Jaika (Watson Assistant)** identifies the intent and extracts entities (like item name, quantity).  
3. **Webhook (Python/Flask)** can log or respond dynamically.  
4. **Twilio** sends the chatbot reply back via SMS or WhatsApp.  
5. The conversation continues in a natural, friendly tone.

##  Setup Instructions

1. Clone this repository
2. Set up IBM Watson Assistant on IBM Cloud
3. Set up a Twilio account and get a phone number (for SMS/WhatsApp)
4. Use Ngrok or host your webhook server for message routing
5. Connect Watson Assistant and Twilio through a simple Flask app or use IBM’s built-in integrations

##  Future Improvements

- Add payment integration or cart summary  
- Store user preferences and past orders  
- Deploy a live version on a website or app  
- Multilingual support for global users


