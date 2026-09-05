<div align="center">

# 📄 OmniDocZ
### *The Private, Multi-Format Desktop Suite for PDFs, Office Documents & Edge AI*
**Part of the NightmareZProtocol Ecosystem • Crafted by NightmareZDev**

[![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12%20%7C%203.13-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D6?logo=windows&logoColor=white)]()
[![Roadmap](https://img.shields.io/badge/Linux%20%26%20macOS-In%20Roadmap-orange.svg)]()
[![Multi-Format](https://img.shields.io/badge/Formats-PDF%20%7C%20DOCX%20%7C%20XLSX%20%7C%20ODS%20%7C%20ODT%20%7C%20Images-blueviolet)]()
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local%20%2F%20Zero%20Telemetry-emerald?logo=shield&logoColor=white)]()
[![NightmareZProtocol](https://img.shields.io/badge/Initiative-NightmareZProtocol-purple.svg)]()
[![License](https://img.shields.io/badge/License-Free-violet)]()
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20Project-ff5e5b?logo=kofi&logoColor=white)](https://ko-fi.com/nightmarezdev)

<p align="center">
  <b>Convert, edit, and merge across PDFs, Word (DOCX/ODT), Excel (XLSX/ODS/CSV), and images seamlessly with live spreadsheet modeling and edge AI—100% offline, zero cloud telemetry.</b>
</p>

[The Vision](#-the-nightmarezprotocol-vision) • [Key Differences](#-why-omnidocz) • [Multi-Format Engine](#-universal-multi-format-conversion--merging) • [Features](#-key-features) • [CLI](#-command-line-interface-cli) • [Quick Start](#-quick-start)

</div>

---

## 🌐 The NightmareZProtocol Vision

**OmniDocZ** is the foundational milestone of **NightmareZProtocol**—an upcoming umbrella ecosystem of 100% local, private, and ad-free desktop applications designed to solve everyday digital problems without subscription barriers or privacy trade-offs.

Modern everyday software is increasingly broken: basic utilities demand recurring monthly fees, inject intrusive ads, track user activity, or force confidential documents onto third-party cloud servers. **NightmareZProtocol** is an alternative built on core principles:

* 🛡️ **Sovereign & Local-First:** Your hardware does the computing; your storage holds the data. No external server dependencies or background telemetry.
* 🚫 **Zero Ads, Zero Dark Patterns:** Pure functional utility without artificial locks, paywalls, or nag screens.
* ⚡ **High-Performance Simplicity:** Fast, lightweight, and purpose-built native software.
* 🧩 **The First Step of Many:** OmniDocZ tackles the universal friction of document management and office workflows. Future standalone tools will expand this ecosystem under the same shared ethos.

---

## 💡 Why OmniDocZ?

Most document tools force an uncomfortable trade-off: **expensive recurring subscriptions** (e.g., Adobe Acrobat, MS Office) or **uploading confidential files to third-party web converters** (e.g., iLovePDF, SmallPDF).

**OmniDocZ** delivers an enterprise-grade desktop suite built from the ground up for **absolute privacy (100% Local / Zero Cloud Telemetry)** with universal format interoperability:

| Feature | Cloud Web Converters | Proprietary Suites (Acrobat, Foxit) | OmniDocZ |
| :--- | :---: | :---: | :---: |
| **Data Privacy** | ⚠️ Uploaded to external servers | ⚠️ Cloud telemetry & account tracking | 🛡️ **100% Local (Never leaves your PC)** |
| **Pricing Model** | Daily quotas / Paid plans | Costly monthly subscription | 💚 **Free & Subscription-free** |
| **Format Flexibility** | Limited conversion pairs | Rigid format silos | 🔄 **Universal PDF ↔ Office ↔ Images ↔ ODF** |
| **Direct Text Editing** | ❌ Opaque white boxes on top | ✅ Supported | ✅ **Double-click to edit live vector text** |
| **Built-in Spreadsheet** | ❌ Not available | ❌ Simple table export only | 📊 **Full Excel grid with live formula engine** |
| **Offline AI & OCR** | ⚠️ Remote server processing | ⚠️ Requires login & cloud access | 🤖 **Local RapidOCR + Rembg (Edge AI)** |
| **Terminal Automation** | ❌ None | ❌ Limited or enterprise-only add-on | 💻 **Built-in CLI with 16 headless commands** |

---

## 🔄 Universal Multi-Format Conversion & Merging

OmniDocZ breaks format silos by natively handling and transforming across open and proprietary document standards:

* **PDF ↔ Microsoft Word & ODF:** Convert PDFs to formatted `.docx` / `.odt` and compile text documents back into pixel-perfect PDFs.
* **PDF ↔ Excel Spreadsheets:** Automatically extract tabular records from financial PDFs into editable `.xlsx`, `.ods`, or `.csv` sheets with formula support.
* **Images ↔ Multi-page Documents:** Convert image collections (PNG, JPG, WEBP, TIFF) into consolidated PDFs, or extract high-DPI raster pages from any document.
* **Universal Document Unifier:** Merge completely different file types (e.g. 1 Word document + 2 PDF contracts + 3 scanned images + 1 Excel balance sheet) into a single, cohesive master document in seconds.
* **Archival Standards (PDF/A):** Export ISO-compliant PDF/A-1b documents for long-term institutional and legal preservation.

---

## ✨ Key Features

### ✏️ True In-Situ Vector Text Editing
Say goodbye to clumsy floating patches and broken alignments:
* **Double-click** any line or paragraph to edit its content in-place.
* **Press Enter** to save changes immediately or **Shift + Enter** to expand new lines downward.
* Automatically detects and preserves original font families, weights, colors, sizes, and layout margins.

### 📊 Integrated Excel Mode & Spreadsheet Engine
* Open, view, and edit `.xlsx`, `.xls`, `.ods`, and `.csv` workbooks directly inside the app.
* Comprehensive **formula calculation**, cell formatting, and row/column manipulation.
* Seamless bidirectional table extraction between PDF and spreadsheet grids.

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
# Merge mixed formats (PDFs, Word, images) into a single master document
python cli.py merge cover.docx chapter1.pdf scan.jpg -o final_document.pdf

# Convert a PDF into an editable Word document (.docx)
python cli.py convert-docx document.pdf -o editable.docx

# Extract PDF financial tables into an Excel spreadsheet (.xlsx)
python cli.py extract balance_sheet.pdf -o data.xlsx

# Encrypt a PDF with AES-256 and custom permissions
python cli.py encrypt contract.pdf -o protected.pdf -p "MySecurePassword"

# Permanently sanitize and redact confidential data
python cli.py redact payroll.pdf -o sanitized_payroll.pdf -t "CONFIDENTIAL"

# Add an invisible OCR text layer to scanned pages
python cli.py ocr-layer scan.pdf -o searchable_scan.pdf --lang en,es
```

---

## 🚀 Quick Start

### System Requirements
* **Operating System:** Windows 10 or Windows 11 (64-bit). *(Linux & macOS planned in the roadmap)*.
* **Python:** 3.10 or higher.

### Running from Source
```bash
# 1. Clone the repository
git clone https://github.com/Nightmare13123/OmniDocZ.git
cd OmniDocZ

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the desktop application
python main.py
```

---

## ☕ Support the Project

OmniDocZ is an independent, open-ecosystem project committed to keeping document processing private, powerful, and free from intrusive paywalls. If this software streamlines your workflow, consider supporting its ongoing development:

<div align="center">

[![Donate on Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20NightmareZDev-ff5e5b?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/nightmarezdev)

<br/>

Engineered with dedication by **NightmareZDev** as the foundational stepping stone of **NightmareZProtocol**.
</div>


