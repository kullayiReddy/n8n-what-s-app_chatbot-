# 🤖 WhatsApp AI Bot (No-Code, Built with n8n & OpenAI)

This is a smart, fully automated WhatsApp bot built using **n8n** and **OpenAI** — with **zero coding**.

The bot can:
- Respond to text-based questions instantly 💬
- Send AI-generated **audio replies** 🔊
- Generate and send **images** based on prompts 🖼️

## 🔧 Tools Used
- [n8n](https://n8n.io) – for automation
- [OpenAI GPT-4](https://openai.com) – for text generation
- [WhatsApp Cloud API](https://developers.facebook.com/docs/whatsapp) – for messaging
- [ElevenLabs](https://www.elevenlabs.io/) (optional) – for voice cloning
- [Replicate or DALL·E](https://replicate.com/) – for image generation

## 📂 Folder Structure

- `workflows/`: Contains exported n8n workflow (`.json`)
- `assets/`: Screenshots, demo GIFs, or videos
- `transcript/`: (Optional) if you used speech-to-text
- `.gitignore`: Ignore unnecessary files

## ▶️ Demo

![Workflow Screenshot](./assets/workflow-screenshot.png)

https://user-images.githubusercontent.com/your_video_demo_link.mp4

## 🛠 How It Works

1. **User sends a message** via WhatsApp.
2. The message triggers an **n8n workflow**.
3. The workflow passes the message to **OpenAI**.
4. Based on the message:
   - Sends a **text reply**
   - Optionally converts it to **audio**
   - Optionally generates an **image**
5. Sends the response back to the user on WhatsApp.

## 📦 Setup Instructions

1. Clone this repo
2. Import the JSON file in `n8n`
3. Connect your WhatsApp Business API & OpenAI key
4. Customize responses or formats if needed

## 📌 Use Cases

- Education bots
- Customer support
- Personal AI assistant
- Automated learning or productivity tools

---

## 📬 Contact

Created by [Your Name](https://www.linkedin.com/in/yourprofile)

---

