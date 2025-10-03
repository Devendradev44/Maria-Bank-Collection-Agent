# Maria-Bank-Collection-Agent
Maria — AI Voice Banking Assistant

🎙️ Live Demo on Vapi

Maria is a voice AI assistant built for banking use-cases, designed with Vapi.ai. She can handle customer queries, verify users securely, and manage sensitive debt-related conversations with empathy and professionalism.

✨ Features

🔐 Customer Verification – Validates customers with account number + OTP.

💳 Debt & Payment Handling – Provides due balance info, politely reminds customers, and escalates to a human agent if required.

🗣️ Conversational Tone – Human-like, empathetic, professional voice interactions.

⚡ Real-Time Voice – Powered by WebSockets + Vapi.ai, ensuring ultra-low-latency conversations.

🌍 Multilingual Support – Can switch to multiple Indian languages (Marathi, Telugu, Kannada, Gujarati, etc.).

🛡️ Secure & Compliant – Uses Vapi’s built-in guardrails, monitoring, and compliance-ready infrastructure.

🛠️ Tech Stack

Vapi.ai – Voice AI infrastructure (ASR → LLM → TTS pipeline)

WebSockets / Streaming API – For real-time audio conversations

Prompt Engineering – To design Maria’s tone, empathy, and flow

Node.js / Express (optional) – Backend integration for APIs

Banking APIs – For account data, balance checks, and OTP verification

🧩 Architecture
User (Voice) 
   ⬇
Maria (Vapi Voice Agent)
   ⬇
Speech-to-Text (ASR) → LLM (Dialogue Logic) → Text-to-Speech (TTS)
   ⬇
Banking APIs (Account Lookup, OTP, Transactions, Payments)


Vapi.ai handles real-time voice pipeline.

Custom logic defines Maria’s flows (verification, debt handling, escalation).

APIs/tools connect Maria to backend banking systems.

🚀 Use Cases

📞 Banking Support Hotline – Handles first-level queries.

🕒 Debt Reminders – Notifies customers about due balances in a polite, professional way.

🔄 24/7 Availability – Always-on support without needing human agents.

🌐 Multilingual Banking Help – Assists customers in local languages.

🔗 Demo

👉 Try Maria live here:
Maria on Vapi.ai

📌 How to Run Locally

Clone this repo:

git clone https://github.com/your-username/maria-voice-assistant.git
cd maria-voice-assistant


Install dependencies (if you’re using Node backend):

npm install


Set up your Vapi API keys in .env.

VAPI_API_KEY=your_key_here


Run locally:

npm start


Connect with Maria via the provided web demo or integrate into a telephony service (Twilio, SIP, etc.).

📸 Screenshots / Demo
