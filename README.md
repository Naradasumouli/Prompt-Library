# 📚 Prompt Library

A simple, browser-based **Prompt Library** that loads prompts from a JSON file hosted on GitHub.  
This project helps organize, view, and manage reusable AI prompts in a clean web interface.

---

## 🚀 Features
- Load prompts dynamically from `data.json`
- Add, edit, and delete prompts directly in the UI
- Export prompts as **JSON** or **CSV**
- Import prompts from JSON, CSV, or Markdown
- Detail view with Markdown rendering
- Local storage fallback if JSON is unavailable

---

## 🌐 Live Preview
👉 [View on GitHub Pages]    (https://htmlpreview.github.io/?https://github.com/Naradasumouli/Prompt-Library/blob/main/index.html)

*(If the link shows only code, enable GitHub Pages in your repo settings:  
**Settings → Pages → Source → `main` branch → `/ (root)` → Save**.  
Your `index.html` will then render as a web page.)*

---

## 📂 Project Structure
Prompt-Library/ │ 
    ├── index.html # Main HTML page (UI + script) 
    ├── data.json # Prompt dataset (acts as a lightweight database) 
    └── README.md

---

## 🛠️ How It Works
- Prompts are stored in `data.json`
- The HTML page fetches the JSON and displays it in a table
- Any updates to `data.json` are reflected in the UI  
  *(with cache-busting to avoid stale data)*

---

## 🔧 Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/Naradasumouli/Prompt-Library.git
