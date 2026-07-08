# MarkItDown Desktop
MarkItDown Desktop is a simple macOS application that allows you to convert documents, spreadsheets, presentations, PDFs, images, and audio files into clean Markdown text with a single click.
---
## 📌 Features
* **Universal File Support:** Convert `.docx`, `.pptx`, `.xlsx`, `.pdf`, `.mp3`, `.jpg`, and web links directly to Markdown.
* **Smart File Detection:** Uses AI-powered file detection to handle complex files automatically.
* **Standalone macOS App:** No terminal commands, Python installation, or technical setup required.
---
## 📥 Download & Installation
1. Go to the **[Releases](../../releases)** section on the right side of this GitHub page.
2. Locate the latest release version (e.g., `v2026.1.1.2`).
3. Under **Assets**, download `MarkItDown.app.zip`.
4. Double-click the downloaded `.zip` file to extract `MarkItDown.app`.
5. Drag `MarkItDown.app` into your **Applications** folder (or just run it in your downloads folder).
---
## 🔐 First Time Opening (macOS Security)
Because the app is downloaded directly from GitHub, macOS Gatekeeper may show a warning when opening it for the first time — something like *"Apple could not verify 'MarkItDown' is free of malware."* This is expected for apps distributed outside the Mac App Store without a paid Apple Developer certificate; it doesn't mean anything is wrong with the app.

**Fastest fix — run this once in Terminal:**
```bash
xattr -cr /Applications/MarkItDown.app
```
*(Adjust the path if you're running it from Downloads instead of Applications.)*

**Or, without Terminal:**
1. Right-click (or `Control` + Click) on **MarkItDown.app** in your Applications folder.
2. Select **Open** from the menu.
3. Click **Open** in the confirmation dialog.

*(Either way, you only need to do this once. After the first run, you can launch it normally.)*
---
## 🔄 Updates
* **Automatic Version Checks:** The app will check for updates on startup and notify you when a new version is available.
* **Manual Updates:** You can always download the latest `.app` bundle from the **[Releases](../../releases)** page to replace your existing version.
---
## 🚀 How to Use
1. Launch **MarkItDown** from your Applications folder or Launchpad.
2. Drag and drop any supported file into the application window (or click **Select File**).
3. The app will process the file and display your clean Markdown text.
4. Click **Copy to Clipboard** or **Save as .md** to export your result.
---
## ❓ Support & Bug Reports
If you run into an issue or have a feature request, please open a ticket on the **[Issues](../../issues)** tab.
