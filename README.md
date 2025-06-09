# 🎴 JoJo-Flashcards!

> **Master any subject, one card at a time.**

**JoJo-Flashcards!** is a fast, offline-first flashcard app that helps you study efficiently. Create decks, customize flashcards with colors, and run self-testing sessions directly in your browser — no accounts, no servers, just your knowledge.

![JoJo Flashcards](assets/icons/icon.png)

🔗 **Demo (Web App)**: [https://joedlopes.github.io/jojo-flashcards/](https://joedlopes.github.io/jojo-flashcards/)

---

## 🛠️ Features

- 🃏 Create and manage unlimited flashcard decks
- 🎨 Customize card colors for front and back
- 🔁 Flip cards with smooth animations
- ✅ Self-assess with "Correct" / "Wrong" buttons
- ⏱️ Optional timer per card
- 🌓 Dark Mode toggle
- 📤 Export & 📥 Import decks via JSON
- 🤖 AI Assistant prompt for generating decks
- 💾 LocalStorage-based persistence (no server required)

---

## 🧰 Tech Stack

- HTML5 + CSS3
- Bootstrap 5
- JavaScript (Vanilla)
- LocalStorage

---

## 🚀 Getting Started (Web Version)

No installation or build step needed. Just open `index.html` in your browser, or deploy it as a static website (e.g., with GitHub Pages).

```bash
# Clone the repo
git clone https://github.com/joedlopes/jojo-flashcards.git
cd jojo-flashcards

# Open locally
open index.html  # or double-click the file
```

---

## 💻 Getting Started (Electron Desktop App)

You can package JoJo-Flashcards! as a desktop app using Electron:

### Install Dependencies

```bash
npm install
```

### Run Locally with Electron

```bash
npx electron .
```

### Build Installers (Linux / Windows)

```bash
npx electron-builder
```

Output will be placed in the `dist/` folder as `.AppImage`, `.deb`, `.exe`, or `.portable` depending on your OS.

---

## 📤 Export / 📥 Import Format

Decks are stored in JSON. Here's an example structure:

```json
[
  {
    "title": "Basic Spanish Vocabulary",
    "cards": [
      { "front": "Hello", "back": "Hola", "frontColor": "#FFFFFF", "backColor": "#E9ECEF" },
      { "front": "Goodbye", "back": "Adios", "frontColor": "#FFFFFF", "backColor": "#E9ECEF" }
    ]
  }
]
```

Decks can be imported by pasting JSON or uploading a `.json` file in the **Import/Export** tab.

---

## 🤖 AI Assistant Prompt

Use the built-in prompt generator under the "AI Assistant Guide" tab to create full decks using LLMs (like ChatGPT, Gemini, etc.).

---

## 📁 Project Structure

```
jojo-flashcards/
├── assets/
│   ├── bootstrap/
│   ├── bootstrap-icons/
│   └── icons/
├── index.html
├── index.js
├── package.json
├── README.md
```

---

## 📄 License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2025 Joed Lopes

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
