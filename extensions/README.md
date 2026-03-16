# 🧩 PCD Console Helper

**Vibe Check: 🟢 Green**

A Chrome extension that lets you paste arbitrary text into a **noVNC** remote console (like your PCD session) by replaying keystrokes into the canvas element. This cleanly solves the long-standing issue of copy/pasting passwords or long commands directly into console sessions!

### 📥 Download

**[⬇️ Download PCD Console Helper](../assets/pcd-console-helper.zip)**

---

## ✨ Features

- **Keystroke injection:** Dispatches synthetic key events directly to the noVNC canvas.
- **Adjustable delay:** Per-character delay to avoid overwhelming slow connections.
- **Secure input mode:** Password-masked textarea that auto-wipes after sending.
- **Saved snippets:** Store and reuse frequently-typed commands.
- **Send history:** Re-send or clear recent items.

---

## 🛠️ Installation

1. [Download the extension ZIP file](../assets/pcd-console-helper.zip) to your computer and extract the folder.
2. Open Google Chrome and navigate your browser to `chrome://extensions`
3. Turn on **Developer mode** (using the toggle in the top-right corner).
4. Click the **Load unpacked** button.
5. Select the newly extracted folder.
6. The Platform9 icon will appear in your Chrome toolbar!

---

## 🚀 Usage

1. Open a browser tab that contains a noVNC console (e.g., an active **PCD console session**).
2. Click the Platform9 Extension icon in your Chrome toolbar.
3. Paste or type your text.
4. Click **Send to Console** (or press `Cmd + Enter` / `Ctrl + Enter`).

> 💡 **Tip:** If you see dropped characters during paste, increase the "Key delay" setting to 20–50 ms. Slower noVNC connections require slightly more time to process each synthetic keystroke event.
