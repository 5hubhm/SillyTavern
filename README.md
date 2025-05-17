# SillyTavern Custom Setup

A custom version of [SillyTavern](https://github.com/SillyTavern/SillyTavern) — a local web UI for chatting with text generation models like OpenAI, KoboldAI, LM Studio, Oobabooga, and others.  
This fork includes personal configuration tweaks and improvements, while protecting private data.

---

## 🚀 Features

- Fast, responsive chat interface
- Supports a wide variety of model backends (OpenAI, Kobold, LM Studio, etc.)
- Multi-character chat support
- Lorebooks, memory, and context handling
- Character card and preset management
- User customization for themes and behavior

---

## 🛠️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 18+ recommended)
- [Git](https://git-scm.com/)
- [Python 3.x](https://www.python.org/) *(optional for certain plugins)*

### Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the application**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   ```
   http://localhost:8000
   ```

---

## 📁 Folder Structure

```plaintext
SillyTavern/
├── public/                  # Static assets
├── scripts/                 # Launchers and setup scripts
├── server/                  # Backend logic
├── bin/functions/           # Utilities and tools
├── data/                    # (Ignored) User data like chat logs and character cards
├── .gitignore               # Excludes all private files
└── README.md
```

---

## 🔐 Privacy

This repository has been configured to **exclude all personal data**, including:

* Chat logs (`data/default-user/chats`)
* Character cards and presets
* Lorebooks, memory, and settings

The `.gitignore` ensures nothing sensitive is pushed to GitHub. You're free to fork, modify, and share this repo safely.

---

## 💡 Tips

* For local models, use backends like **LM Studio**, **KoboldAI**, or **Oobabooga** and connect via SillyTavern’s API settings.
* To use OpenAI or other services, insert your API key in the UI settings (never store it in code).
* Backups of characters and conversations are stored in your `data/` folder (not versioned here).

---

## 📦 Optional Add-ons

If you're using local LLMs, consider installing:

* [LM Studio](https://lmstudio.ai/)
* [KoboldCpp](https://github.com/LostRuins/koboldcpp)
* [OpenWebUI](https://github.com/open-webui/open-webui) *(for Ollama/LLMs with GUI)*

These tools let you run models like LLaMA, Mistral, and OpenHermes offline.

---

## 📄 License

This project is based on the original SillyTavern and is distributed under the MIT License.  
Please refer to the [LICENSE](https://github.com/SillyTavern/SillyTavern/blob/main/LICENSE) for more information.

---

## 🙌 Credits

* [SillyTavern Devs](https://github.com/SillyTavern/SillyTavern)
* The open-source LLM community