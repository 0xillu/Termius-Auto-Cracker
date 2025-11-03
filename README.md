# 🧩 Termius Modifier (Trial + Skip Login)

A lightweight Python tool to modify **Termius Desktop**’s `app.asar` file, enabling the **Trial** mode or **Skip Login** screen — or both.

---

## ⚙️ Features

- 🧠 **Enable Trial Mode** (`--trial`)  
  Unlocks Termius’ professional features temporarily.

- 🚪 **Skip Login Screen** (`--skip-login`)  
  Opens Termius without requiring login.

- 💾 **Automatic Backup**  
  Creates `app.asar.bak` before any modifications.

- 🔄 **Repack & Restore**  
  Extracts, modifies, and repacks `app.asar` automatically.

- 🪶 Clean Python 3 script — no dependencies, no bloat.

---

## 📦 Requirements

You’ll need:

- **Python 3.8+**
- **Node.js + asar**

Install the `asar` tool globally using npm:

```bash
npm install -g asar

# Folder Structure
TermiusModifier/
├── lang.py
├── rules/
│   ├── trial.txt
│   └── skip_login.txt
└── README.md

```Enable Pro mode 
python lang.py --trial
