# PDF Chat (PDF-GPT)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#license)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Built With](https://img.shields.io/badge/Built%20With-HTML%2C%20JS%2C%20pdf.js-blue)

A lightweight web app that lets you **upload a PDF** and **chat with its contents**. Text is extracted locally via `pdf.js`, and answers are generated with **Google Gemini**. Perfect for quick document Q&A prototypes.

---

## Features

* 📄 Client-side PDF parsing (no backend needed for extraction)
* 🤖 Ask questions answered strictly from the document
* ⚡ Clean drag-and-drop UI
* 📱 Mobile-responsive

---

## Getting Started

1. Clone the repo.
2. Open `index.html` in your browser **or** run:

   ```bash
   python -m http.server 8080
   ```

### Replace Your Gemini API Key

Inside `index.html`, update this line with **your own** key:

```js
const apiKey = "YOUR_GEMINI_API_KEY";
```

---
