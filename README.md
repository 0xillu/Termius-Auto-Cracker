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

Install the `asar` tool using npm:

```bash
npm install -g asar
```

# Folder Structure
### make sure that the lang.py and rules folder is in the resources folder of termius
```
C:\Users\%USERNAME%\AppData\Local\Programs\Termius\resources
├── lang.py
├── rules/
│   ├── trial.txt
│   └── skip_login.txt
└── app.asar
```

## Enable Pro mode 
``` 
python lang.py --trial
```
## Skip Login
```
python lang.py --skip-login
```
## Skip login and Enable Pro
```
python lang.py --trial --skip-login
```





