# 📄 MarkItDown App Updates

This repository contains **release builds only** for the MarkItDown Converter desktop application.

It does NOT contain source code.

---

# 🚀 What is this?

The MarkItDown Converter is a desktop application that allows you to:

- Drag & drop files anywhere in the window
- Convert files into Markdown format
- View conversion progress in real time
- Use a simple, clean interface
- Receive update notifications automatically

---

# 📦 Downloads

👉 Get the latest version here:

https://github.com/NeedlerCR/MarkItDown-App-Updates/releases

Download the latest `.zip` or `.app` file.

---

# 🔄 Automatic Updates

The app automatically checks this repository using GitHub Releases


If a newer version is available, you will be notified when the app starts.

---

# 🏷 Versioning System

We use semantic versioning:

- v1.0.0 → Initial release
- v1.0.1 → Bug fixes
- v1.1.0 → New features
- v2.0.0 → Major changes

---

# 🛠 How to publish a new version

To release a new version:

1. Build the app using PyInstaller
2. Zip the `.app` file:

```bash
zip -r MarkItDownApp.zip dist/MarkItDownApp.app
