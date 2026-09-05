<div align="center">

# 📄 OmniDocZ
### *The Private, All-in-One Desktop Suite for PDFs, Spreadsheets & Edge AI*
**Engineered under the NightmareZProtocol ecosystem**

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12%20%7C%203.13-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D6?logo=windows&logoColor=white)]()
[![Roadmap](https://img.shields.io/badge/Linux%20%26%20macOS-In%20Roadmap-orange.svg)]()
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local%20%2F%20Zero%20Telemetry-emerald?logo=shield&logoColor=white)]()
[![License](https://img.shields.io/badge/License-Free-violet)]()
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Project-ff5e5b?logo=kofi&logoColor=white)](https://ko-fi.com/nightmarezdev)

<p align="center">
  <b>Edit PDF text directly line-by-line, manipulate live spreadsheets with formulas, run edge AI OCR, and protect confidential documents without sending a single byte to the cloud.</b>
</p>

[Key Differences](#-why-omnidocz) • [Features](#-key-features) • [CLI Automation](#-command-line-interface-cli) • [Quick Start](#-quick-start) • [Support](#-support-the-project)

</div>

---

## 💡 Why OmniDocZ?

Most document tools force an uncomfortable trade-off: **expensive recurring subscriptions** (e.g., Adobe Acrobat) or **uploading sensitive files to third-party web servers** (e.g., cloud converters like iLovePDF or SmallPDF).

**OmniDocZ** delivers an enterprise-grade desktop suite built from the ground up for **absolute privacy (100% Local / Zero Cloud Telemetry)** without sacrificing performance:

| Feature | Cloud Web Converters | Proprietary Suites (Acrobat, Foxit) | OmniDocZ |
| :--- | :---: | :---: | :---: |
| **Data Privacy** | ⚠️ Uploaded to external servers | ⚠️ Cloud telemetry & account tracking | 🛡️ **100% Local (Never leaves your PC)** |
| **Pricing Model** | Daily quotas / Paid plans | Costly monthly subscription | 💚 **Free & Subscription-free** |
| **Direct Text Editing** | ❌ Opaque white boxes on top | ✅ Supported | ✅ **Double-click to edit live vector text** |
| **Built-in Spreadsheet** | ❌ Not available | ❌ Simple table export only | 📊 **Full Excel grid with live formula engine** |
| **Offline AI & OCR** | ⚠️ Remote server processing | ⚠️ Requires login & cloud access | 🤖 **Local RapidOCR + Rembg (Edge AI)** |
| **Terminal Automation** | ❌ None | ❌ Limited or enterprise-only add-on | 💻 **Built-in CLI with 16 headless commands** |

---

## ✨ Key Features

### ✏️ True In-Situ Vector Text Editing
Say goodbye to clumsy floating patches and broken alignments:
* **Double-click** any line or paragraph to edit its content in-place.
* **Press Enter** to save changes immediately or **Shift + Enter** to expand new lines downward.
* Automatically detects and preserves original font families, weights, colors, sizes, and layout margins.

### 📊 Integrated Excel Mode & Spreadsheet Engine
* Open, view, and edit `.xlsx` and `.csv` workbooks directly inside the app.
* Comprehensive **formula calculation**, cell styling, and row/column manipulation.
* **Bidirectional conversion:** Automatically detects structured tables in PDFs and transforms them into clean spreadsheet workbooks with one click.

### 🤖 Decoupled Edge AI & Computer Vision
* **Searchable OCR Layer**: Injects an invisible text layer over scanned documents or photographs, enabling text selection, copying, and full-text search.
* **Smart Perspective Correction & Auto-Deskew**: Automatically detects document boundaries in tilted photos or crooked scans and corrects perspective distortion.
* **Offline Background Removal (`rembg`)**: Isolate stamps, signatures, and logos using local neural networks without an internet connection.
* **Lightweight modular architecture**: The core application remains compact; optional AI weights can be downloaded on-demand.

### 🔒 Hardened Security & Cryptography
* **AES-256 Encryption**: Password protection with granular permissions (printing, copying, content modification).
* **Irreversible Permanent Redaction (Blackout)**: Sanitizes sensitive data by removing both visual strokes and underlying raw text streams (preventing extraction via inspection tools).
* **Cryptographic Digital Signatures** (PAdES / PKCS#7).

### ⚡ Batch Automation Engine
* Apply compression, digital watermarks, page numbering, conversion, or orientation correction to hundreds of documents simultaneously in seconds.

### 🌐 Global & Accessible UI
* Refined modern **Dark Mode** interface with an **Interactive Onboarding Tour** for first-time users.
* Fully translated into **6 languages**: English, Spanish, French, German, Portuguese, and Italian.

---

## 💻 Command Line Interface (CLI)

For system administrators, developers, and headless pipelines, OmniDocZ includes a dedicated console engine (`cli.py`):

```bash
# Merge multiple PDFs and images into a single file
python cli.py merge cover.pdf chapter1.pdf photo.jpg -o final_document.pdf

# Encrypt a PDF with AES-256 and custom permissions
python cli.py encrypt contract.pdf -o protected.pdf -p "MySecurePassword"

# Permanently sanitize and redact confidential data
python cli.py redact payroll.pdf -o sanitized_payroll.pdf -t "CONFIDENTIAL"

# Extract PDF financial tables into an Excel spreadsheet (.xlsx)
python cli.py extract balance_sheet.pdf -o data.xlsx

# Add an invisible OCR text layer to scanned pages
python cli.py ocr-layer scan.pdf -o searchable_scan.pdf --lang en,es

