# MarkItDown Converter Environment

A standardized Python workspace for converting various file formats (PDF, Word, Excel, PowerPoint, Audio, Images, HTML, etc.) into clean Markdown text using Microsoft's **MarkItDown** library.

---

## 📌 Features

* **Multi-Format Conversion:** Convert `.docx`, `.pptx`, `.xlsx`, `.pdf`, `.mp3`, `.jpg`, and web content directly into structured Markdown.
* **Full Feature Parity:** Equipped with `markitdown[all]`, including Google's `magika` for AI file-type detection, `pdfplumber`, and Azure Document Intelligence support.
* **Isolated Environment:** Configured to run on Python 3.12 inside a dedicated virtual environment to ensure cross-platform compatibility and binary wheel support.

---

## 📥 Downloading the Application

You can obtain the application in two ways depending on how you intend to use it:

### Method 1: Download Pre-built Releases (Recommended for non-developers)
1. Go to the **[Releases](../../releases)** page of this GitHub repository.
2. Locate the latest version tag (e.g., `v2026.1.1.1`).
3. Under **Assets**, download the binary file suited for your operating system:
   * **macOS:** `markitdown-macos.zip`
   * **Windows:** `markitdown-windows.exe`
   * **Linux:** `markitdown-linux`
4. Unzip (if applicable) and run the executable directly from your terminal or command prompt.

### Method 2: Install from Source (Recommended for developers)
If you wish to modify the code or run it natively using Python:

```bash
# 1. Clone the repository
git clone <your-repository-url>
cd markitdown-env

# 2. Create and activate a Python 3.12 virtual environment
python3.12 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install required dependencies
pip install --upgrade "markitdown[all]"
