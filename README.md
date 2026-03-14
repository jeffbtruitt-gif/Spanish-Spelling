# ⭐ Estrellas de Ortografía

A Spanish spelling practice app for kids. Students listen to a word or phrase spoken in Spanish and type it using the on-screen keyboard. Parents manage weekly spelling lists from a separate tab.

**Live demo (once deployed):** `https://YOUR-USERNAME.github.io/estrellas-ortografia`

---

## ✨ Features

- 🔊 Spanish text-to-speech pronunciation (slow rate for learners)
- ⌨️ Large touch-friendly on-screen keyboard with Spanish accent keys (Á É Í Ó Ú Ü Ñ)
- ✅ Live scoreboard during the quiz — correct words on the left, incorrect on the right
- 🔴 Wrong answers show exactly which letters were mistyped (highlighted in red)
- 📋 Parent admin panel (in English) to create, edit, and manage weekly word lists
- 💾 Word lists saved in the browser automatically (localStorage)
- 🎉 Confetti and encouraging messages for correct answers
- 📱 Works on touchscreen laptops, tablets, and desktop browsers

---

## 🚀 How to Deploy on GitHub Pages (Free Hosting)

GitHub Pages lets you host this app for free at a public URL. Follow these steps:

### Step 1 — Create a GitHub account
If you don't have one, go to [github.com](https://github.com) and sign up. It's free.

### Step 2 — Create a new repository
1. Click the **+** button in the top right corner of GitHub
2. Select **"New repository"**
3. Name it: `estrellas-ortografia`
4. Make sure it is set to **Public**
5. Leave everything else as default
6. Click **"Create repository"**

### Step 3 — Upload the files
1. On your new repository page, click **"uploading an existing file"** (or drag and drop)
2. Upload both files from this folder:
   - `index.html`
   - `README.md`
3. Scroll down and click **"Commit changes"**

### Step 4 — Enable GitHub Pages
1. Click the **"Settings"** tab at the top of your repository
2. In the left sidebar, click **"Pages"**
3. Under **"Branch"**, select `main` from the dropdown
4. Leave the folder as `/ (root)`
5. Click **"Save"**

### Step 5 — Visit your app
After about 1–2 minutes, your app will be live at:
```
https://YOUR-USERNAME.github.io/estrellas-ortografia
```
Replace `YOUR-USERNAME` with your actual GitHub username.

> 💡 **Tip:** Bookmark this URL and share it with your student. It works on any device with Chrome.

---

## 📖 How to Use the App

### For Parents — Setting up word lists
1. Open the app and click the **"Word Lists"** tab
2. Type a name for the list (e.g. "Week 5 — Preterite verbs")
3. Paste or type the Spanish words/phrases, **one per line**
4. Click **"Create List"** — it becomes the active list automatically
5. Each week, create a new list. The newest list is always selected by default.
6. Use the **✏️ Edit** button to change a list's name or words at any time

### For Students — Practicing
1. Open the app and make sure you're on the **"Practicar"** tab
2. Select the list your parent assigned
3. Click **"¡Empezar!"** to start
4. Tap the 🔊 button to hear the word or phrase spoken in Spanish
5. Type it out using the on-screen keyboard — tap **ESPACIO** for spaces
6. Tap **OK** (or press Enter) to submit your answer
7. Green = correct ✅, Red = incorrect ❌
8. At the end, you can review your mistakes and tap **"Repetir errores"** to practice just the ones you got wrong

---

## 🔊 Sound Troubleshooting

The app uses your browser's built-in Spanish text-to-speech.

- **Use Google Chrome** for the best Spanish voice support
- Make sure your **system volume is turned up**
- On Windows, you may need to install Spanish language voices:
  - Go to **Settings → Time & Language → Language & Region**
  - Add **Español (México)** or **Español (Estados Unidos)**
  - Download the speech pack when prompted
- On Mac, go to **System Settings → Accessibility → Spoken Content** and add a Spanish voice

---

## 🛠️ Technical Notes

- **No server required** — this is a single HTML file with no dependencies
- **No internet required** — works fully offline once loaded (no CDN calls at runtime)
- **Data is stored locally** — word lists are saved in the browser's localStorage. They persist between sessions on the same device/browser but do not sync across devices.
- **To share lists across devices** — you'll need to re-enter lists on each device, or edit the `index.html` file to pre-load your lists in the default data section

---

## 📁 File Structure

```
estrellas-ortografia/
├── index.html    ← The entire app (single file, no build step needed)
└── README.md     ← This file
```

---

## 🔄 Updating the App

To update the app after making changes:
1. Edit `index.html` locally
2. Go to your GitHub repository
3. Click on `index.html`
4. Click the **pencil (edit) icon**
5. Paste your updated code
6. Click **"Commit changes"**

Your live site will update within a minute or two.
