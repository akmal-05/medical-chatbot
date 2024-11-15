# Medical Chatbot with Context Verification

A robust AI-powered chatbot designed to answer medical-related queries using a two-step architecture. The first model generates responses, while the second model, powered by Groq API, ensures responses are contextually relevant to the medical domain.

---

## 🚀 Features

- **Medical Expertise**: Handles questions about diseases, symptoms, and prevention.
- **Context Validation**: A second verification layer ensures only medical-related queries are addressed.
- **Pretrained Models**: Utilizes `bert-base-uncased` for response generation and `Groq Llama` for context verification.
- **User-Friendly Interface**: Gradio-powered GUI for seamless interaction.

---

## 📂 Project Structure

- `intents.json`: JSON dataset containing predefined intents, patterns, and responses.
- `OK-ChatBot.ipynb`: The core chatbot script, including training and response logic.
- `requirements.txt`: List of required dependencies for the project.

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/akmal-05/medical-chatbot
   cd medical-chatbot
