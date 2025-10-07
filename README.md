# Maria — AI Voice Banking Assistant  

🎙️ [**Live Demo on Vapi.ai**](https://vapi.ai?demo=true&shareKey=bcdfc539-8b6d-4c98-aab5-7bcb96c731ac&assistantId=94cee14e-7454-4152-b15b-dadacb3d797f)  

📄 [**Assignment PDF**](docs/Prompt_Engineer_Assignment_R0.pdf)  
📘 [**Project Summary (PDF)**](Maria_AI_Voice_Assistant_Project.pdf)

---

## 🧠 Overview  

**Maria** is a **voice-based conversational AI agent** built using **Vapi.ai**, designed for **XYZ Bank**.  
She serves as an empathetic and professional **collections representative**, helping customers handle overdue payments with emotional intelligence and clarity.  

This project was created as part of a **Prompt Engineering assignment**, focusing on crafting system instructions, tone, and logical conversation flow to simulate real-world banking support.

---

## ✨ Features  

- 🔐 **Identity Verification** — Validates customers using DOB or last 4 digits of SSN.  
- 💳 **Debt & Payment Handling** — Clearly communicates overdue details and offers flexible plans.  
- 🧠 **Human-Like Conversations** — Uses natural, short, and emotionally intelligent responses.  
- ⚡ **Real-Time Voice** — Powered by **Vapi WebSockets** for low-latency interactions.  
- 🌍 **Multilingual** — Supports Indian languages like Marathi, Telugu, Kannada, and Gujarati.  
- 🛡️ **Compliance Guardrails** — Avoids hallucinations and maintains professional tone.  

---

## 🛠️ Tech Stack  

| Component | Provider | Purpose |
|------------|-----------|----------|
| **Vapi.ai** | — | Voice AI orchestration & pipeline |
| **Deepgram Nova-2** | STT | Speech-to-text transcription |
| **OpenAI GPT-4o mini** | LLM | Handles reasoning & tone |
| **ElevenLabs TurboV2.5** | TTS | Produces natural, empathetic voice |
| **Node.js / APIs (Planned)** | — | For banking data integration |

---

## 🗣️ Ideal Conversation Flow  

Maria: Hello, this is Maria from XYZ Bank’s collections team. Am I speaking with Mr. Robin Smith?

Customer: Yes, that’s me.

Maria: Great. To verify, could you share the last four digits of your Social Security Number?

Customer: 3456.

Maria: Thank you, Mr. Smith. Your account ending in 1903 has an overdue balance of seven hundred ten dollars, due April first, two thousand twenty-five. Would you like to make the full payment now?

Customer: I can’t pay that much right now.

Maria: That’s okay. We can offer a four-month plan at one hundred ninety-four dollars and thirty-six cents per month. Would that help?

Customer: That’s still a bit high.

Maria: No problem. Based on what you can afford, we can extend it to eight months — ninety-seven dollars and eighty cents per month, at ten point two percent interest. Would that work better?

Customer: Yes, that’s manageable.

Maria: Perfect. I’ve triggered a payment notification in your XYZ Bank app. Please complete it when convenient. Thank you for your cooperation.

yaml
Copy code

---

## 🧩 Edge Cases  

- ❌ **Refuses verification** → Offer DOB as an alternative.  
- 💬 **Disputes the debt** → Offer to send invoice for review.  
- 🧾 **Questions interest rates** → Explain percentage clearly.  
- 💸 **Unable to pay** → Show empathy, discuss smaller plans.  
- 😠 **Angry or frustrated** → Stay calm, acknowledge emotion.  

---

## 💡 Prompt Design Strategy  

Maria’s **system prompt** emphasizes:  
- Empathy and professionalism  
- One question at a time  
- Brief, natural responses (1–2 sentences)  
- Smooth handling of interruptions  
- Context retention  

Iterative testing on **Vapi.ai** refined tone, timing, and offer sequencing for a lifelike experience.

---

## 🗂️ Repository Files  

/docs
├── Prompt_Engineer_Assignment_R0.pdf # Original assignment instructions
├── conversation-flow.md # Dialogue and logic flow
├── final-prompt.txt # System prompt used in Vapi
└── empathy-rules.md # Tone and language principles
Maria_AI_Voice_Assistant_Project.pdf # Polished project summary
README.md # This file

yaml
Copy code

---

## 🏁 Outcome  

Maria demonstrates how **prompt engineering** and **voice AI infrastructure** can combine to create natural, secure, and emotionally intelligent customer interactions in the banking industry.  

---

## 🧾 License  

MIT License © 2025 Dev  
