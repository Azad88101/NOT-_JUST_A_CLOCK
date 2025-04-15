# Death Year Estimator - Browser Extension

This project is a simple browser extension that estimates and displays a user's death year based on a calculation or logic defined in the code.

## 🚀 Features

- Estimates user's **death year**.
- Optional dialog to allow the user to **manually enter their own death year**.
- Built with intention to be used as a **Chrome Extension**.
- Uses `manifest.json` to configure the extension.
- Designed with **default values** to eliminate repeated user input every time.

> **Note:**  
> The line in the code `// deathYearDialog.showModal();` is intentionally commented  to avoid prompting the user every time. If you want the user to input the death year manually each time, simply uncomment that line.

---

## 🧩 How to Install the Extension

1. Open **Google Chrome** (or any Chromium-based browser).
2. Go to `chrome://extensions/`.
3. **Enable Developer Mode** (toggle switch at the top-right corner).
4. Click on **"Load unpacked"** on the top-left corner.
5. Select the folder where your extension files are located (`manifest.json`, `index.html`, JS, CSS, etc.).
6. Done! Your extension is now added to your browser.

---

## 📁 Files Included

- `manifest.json` – Configuration for the browser extension.
- `index.html` – UI displayed when the extension is clicked.
- `script.js` – Contains logic for calculating and displaying death year.
- `style.css` – Optional styling for UI.
- `README.md` – You're reading it :)

---

## 🛠 Developer Notes

- If you want to prompt the user every time for their own death year, **uncomment** the following line in your JavaScript: line no. 516
  ```js
  // deathYearDialog.showModal();
  ```
