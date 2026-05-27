Bhai, screenshot dekh ke samajh aa gaya problem kahan hui hai. Jab aapne copy-paste kiya, to "Step 1" ke baad wala pura content ek single code block (```) ke andar chala gaya, isliye baki ka formatting (bold, links, aur code boxes) plain text ki tarah show ho raha hai.
Maine isko properly fix kar diya hai aur spacing theek kar di hai taaki markdown break na ho.
Aap bas niche diye gaye box ke top-right corner par jo **"Copy"** ka icon hai us par click karein, aur apne GitHub ke README.md file me direct Ctrl+V (ya Cmd+V) kar dein. Kuch bhi manual edit karne ki zaroorat nahi padegi (bas repo link aur API key ke alawa).
Yahan raha aapka perfect code:
```markdown
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
* [Node.js](https://nodejs.org/) (v18 or higher recommended)
* A Google Cloud / AI Studio Account

## 🔑 How to Get a Free Gemini API Key (Important)

To make this application work, you need a valid Google Gemini API Key. Follow these 3 crucial steps carefully:

**1. Enable the Gemini API:**
* Go to the [Google Cloud Console](https://console.cloud.google.com/).
* Search for **"Generative Language API"** (This is the Gemini API).
* Click **Enable**. *(Note: Your API key will not work if this step is skipped).*

**2. Generate the API Key:**
* Sign in to [Google AI Studio](https://aistudio.google.com/).
* Ensure you are in the *same project* that you used in the Google Cloud Console.
* Click on **"Get API Key"** and generate your key.

**3. Payment Verification:**
* Google AI Studio requires a one-time payment verification to prevent spam.
* You will need to verify your payment method (Only a temporary deduction of ₹2 / minimal amount occurs, which is usually refunded. You can easily do this via QR code or cards).

## 🚀 Installation & Setup

**Step 1: Clone the repository**
```bash
git clone https://github.com/your-username/nodejs-gemini-terminal-chat.git
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
```

```
