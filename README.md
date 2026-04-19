# Cosmic AI V34 🚀

**Your local, private AI assistant running right in the browser**

[Live Demo](https://cosmic785.github.io/my-local-ai/) · [Report a Bug](https://github.com/cosmic785/my-local-ai/issues)

Cosmic AI V34 is a lightweight, client-side AI chat interface designed for privacy and speed. No data leaves your machine. Customize your name, theme, and avatar to make it yours.

### ✨ Features

- **100% Local & Private**: Runs entirely in your browser. No API keys, no tracking.
- **Customizable Profile**: Set your username and upload a custom avatar
- **Theme Support**: Switch between light/dark modes for comfy chatting
- **Clean UI**: Minimal, fast interface focused on the conversation
- **Open Source**: Fork it, modify it, self-host it

### 🛠️ Tech Stack

| Component | Details |
| --- | --- |
| Frontend | HTML, CSS, JavaScript |
| Hosting | GitHub Pages |
| Storage | Browser localStorage for settings + chat history |
| AI Engine | Runs locally / via WebAssembly / connects to LocalAI backend |

> Note: Update the "AI Engine" line to match what you're actually using - Ollama, LocalAI, llama.cpp WASM, Transformers.js, etc.

### 🚀 Quick Start

**To use it:**
1. Go to https://cosmic785.github.io/my-local-ai/
2. Set your **User Name** and **Avatar**
3. Pick your **Theme**
4. Start chatting

**To run locally / self-host:**
1. Clone the repo
   ```bash
   git clone https://github.com/cosmic785/my-local-ai.git
   cd my-local-ai
