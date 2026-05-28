## 🧰 Tech Stack & Core Libraries
# Node.js Gemini Terminal Chat CLI
A powerful Node.js terminal chatbot CLI using Google Gemini AI API. This project helps developers interact with Gemini AI directly from the command line with fast responses, streaming chat, and developer-friendly workflows. Perfect for developers searching for ChatGPT CLI, Claude CLI, Copilot alternatives, and AI terminal assistants.

This project is built using modern JavaScript practices and lightweight dependencies to ensure fast execution and high performance:

* **Node.js:** The core runtime environment for executing JavaScript in the terminal.
* **@google/genai (v2.6.0+):** The official, newly released Google SDK used to connect and interact with the `gemini-2.5-flash` model.
* **readline-sync:** A synchronous library used to capture user input interactively directly from the command line without complex callback structures.
* **dotenv:** A zero-dependency module that loads environment variables (like your `GEMINI_API_KEY`) from a `.env` file into `process.env` for secure credential management.

## ⚙️ Core System Capabilities

* **Stateful Chat Sessions:** The system does not just answer single prompts; it passes the `history: []` array in real-time to maintain conversation memory.
* **Non-Blocking I/O:** Utilizes Javascript's `async/await` architecture to wait for Google's API responses without freezing the terminal.
* **ES Modules (ESM):** Configured with `"type": "module"` for modern `import/export` syntax compatibility.

# Gemini CLI Chatbot 🤖

A lightweight, high-performance command-line interface (CLI) chatbot powered by Node.js and Google's latest **Gemini 2.5 Flash** model. 

This project uses the newly updated `@google/genai` SDK to provide a continuous, context-aware conversational experience right inside your terminal.

## ✨ Features

* **Continuous Conversation:** Keep chatting without restarting the script.
* **Context History Management:** The AI remembers the context of the current session for highly specific and relevant answers.
* **Asynchronous Processing:** Built with modern JS `async/await` for fast, non-blocking API calls.
* **Latest SDK Integration:** Utilizes the official `@google/genai` package and the `gemini-2.5-flash` free tier model.

## 🛠️ Prerequisites

Before running this project, ensure you have the following installed:
```markdown
* [Node.js](https://nodejs.org/) (v18 or higher recommended)
* A Google Cloud / AI Studio Account
```

## 🔑 How to Get a Free Gemini API Key (Important)

To make this application work, you need a valid Google Gemini API Key. Follow these 3 crucial steps carefully:

**1. Enable the Gemini API:**
```markdown
* Go to the [Google Cloud Console](https://console.cloud.google.com/).
* Search for **"Generative Language API"** (This is the Gemini API).
* Click **Enable**. *(Note: Your API key will not work if this step is skipped).*
```
**2. Generate the API Key:**
```markdown
* Sign in to [Google AI Studio](https://aistudio.google.com/).
* Ensure you are in the *same project* that you used in the Google Cloud Console.
* Click on **"Get API Key"** and generate your key.
```
**3. Payment Verification:**
* Google AI Studio requires a one-time payment verification to prevent spam.
* You will need to verify your payment method (Only a temporary deduction of ₹2 / minimal amount occurs, which is usually refunded. You can easily do this via QR code or cards).

## 🚀 Installation & Setup

**Step 1: Clone the repository**
```bash
git clone https://github.com/hiteshwarke/nodejs-gemini-terminal-chat.git
cd nodejs-gemini-terminal-chat
```

**Step 2: Install dependencies**
```bash
npm install

```
**Step 3: Configure ES Modules**
Ensure that your package.json file includes the "type": "module" configuration:
```json
{
  "name": "genai",
  "version": "1.0.0",
  "type": "module",
  "main": "index.js",
  "dependencies": {
    "@google/genai": "^2.6.0",
    "dotenv": "^17.4.2",
    "readline-sync": "^1.4.10"
  }
}

```
**Step 4: Set up Environment Variables**
Create a .env file in the root directory of your project and add your API key:
```env
GEMINI_API_KEY=your_generated_api_key_here

```
## 💻 Usage
Run the application using Node.js:
```bash
node index.js

```
Once started, the terminal will prompt you with You:. Simply type your message, press Enter, and chat seamlessly with Gemini!
## 📄 License
This project is licensed under the ISC License. Feel free to use, modify, and distribute it.
```markdown
ChatGPT alternative
Gemini CLI
Claude AI terminal
AI coding assistant
Node.js AI chatbot
Terminal AI assistant
LLM command line tool
OpenAI compatible chatbot
Developer productivity tool
GitHub Search
Google Search
ChatGPT recommendations
Gemini recommendations
Claude search/context
Copilot indexing
npm ecosystem searches
```
