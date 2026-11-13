# 🧠 Loqmi — Official Landing Page

**Your AI. Your Machine. Your Privacy.**

The official landing page for **[Loqmi](https://github.com/loqmi-desktop/loqmi)**, a privacy-first desktop AI assistant designed to bring the power of Large Language Models directly to your machine.

🌐 **Website:** [loqmi-desktop.github.io](https://loqmi-desktop.github.io)  
💻 **Main Application:** [loqmi-desktop/loqmi](https://github.com/loqmi-desktop/loqmi)

---

## ✨ About Loqmi

Loqmi is a local-first desktop AI assistant that runs powerful open-source Large Language Models (LLMs) entirely on your hardware using [`llama.cpp`](https://github.com/ggml-org/llama.cpp).

With intelligent intent routing, Retrieval-Augmented Generation (RAG), and optional web search, Loqmi provides an AI experience without compromising your privacy.

**Your conversations stay on your machine. Your data stays yours.**

## 🚀 Features

- 🔒 **Privacy First:** Run AI models locally without sending your conversations to external AI providers.
- 🧠 **Smart Intent Routing:** Automatically routes prompts to specialized models based on the task.
- 📚 **Local RAG:** Retrieve relevant information from your documents using ChromaDB.
- ⚡ **Local LLM Inference:** Powered by `llama.cpp` and optimized GGUF models.
- 🌐 **Optional Web Search:** Access web information when you need external context.
- 💻 **Platform Awareness:** Automatically detects the visitor's operating system and displays the appropriate download experience.

## 📥 Download Loqmi

| Platform | Availability |
|---|---|
| macOS (Apple Silicon) | Available |
| Windows | Coming Soon |

### macOS

Download the latest available Apple Silicon build:

[**⬇️ Download Loqmi for macOS**](https://github.com/loqmi-desktop/loqmi/releases/download/v0.1.0-alpha/loqmi_0.1.0_aarch64.dmg)

- Version: `0.1.0-alpha`
- Architecture: Apple Silicon (ARM64)
- Minimum macOS version: 12.0+

> Windows support is currently under development.

## 🛠️ Tech Stack

The landing page is intentionally lightweight and built without a frontend framework.

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| Vanilla JavaScript | Client-side OS detection |
| Tailwind CSS | Styling and responsive design |
| GitHub Pages | Website hosting |

## 📂 Repository Structure

```text
loqmi-desktop.github.io/
│
├── index.html       # Main landing page
└── README.md        # Project documentation
```

## 💻 Getting Started

Want to run the landing page locally or contribute to its development?

### 1. Clone the repository

```bash
git clone https://github.com/loqmi-desktop/loqmi-desktop.github.io.git
```

### 2. Navigate to the project directory

```bash
cd loqmi-desktop.github.io
```

### 3. Run locally

You can simply open `index.html` in your browser.

Alternatively, use the **Live Server** extension in VS Code to launch a local development server.

The website will be available at the local address provided by Live Server.

## 🌍 Deployment

The landing page is hosted using **GitHub Pages**.

Any changes pushed to the configured publishing branch are deployed through GitHub Pages.

To deploy your own version:

1. Fork this repository.
2. Go to your repository's **Settings → Pages**.
3. Configure the deployment source and publishing branch.
4. Push your changes and access your published website.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

If you'd like to contribute:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "feat: add your feature"
   ```

4. Push your branch and open a Pull Request.

## 📜 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the source code in accordance with its terms.

---

<div align="center">

**Built with ❤️ for a more private AI future.**

[Website](https://loqmi-desktop.github.io) · [Main Repository](https://github.com/loqmi-desktop/loqmi) · [Report an Issue](https://github.com/loqmi-desktop/loqmi-desktop.github.io/issues)

</div>