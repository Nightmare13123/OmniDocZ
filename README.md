[README.md](https://github.com/user-attachments/files/35222455/README.md)
<div align="center">

# OmniDocZ

**Edit PDFs, work with spreadsheets, and turn scans into searchable documents on your PC.**

Combine Word files, PDFs, spreadsheets, and photos. Recover text and tables, prepare files for sharing, and process a whole batch from one Windows desktop app.

<p>
  <a href="https://github.com/Nightmare13123/OmniDocZ/releases/latest">
    <img src="https://img.shields.io/badge/Download_for_Windows-Latest_Release_%28.exe%29-2563EB?style=for-the-badge&amp;labelColor=1D4ED8&amp;logo=windows&amp;logoColor=white" alt="Download OmniDocZ for Windows from GitHub Releases" width="481" height="36">
  </a>
</p>

**Windows 10 / 11 (64-bit) · Free and ad-free · Files processed locally**

[Download](#download-and-install) · [PDFs and documents](#pdfs-and-documents) · [Spreadsheets](#excel-studio-beta) · [OCR](#ocr-and-text-extraction) · [Images](#image-tools) · [Security](#pdf-security-and-forms) · [Batch processing](#batch-processing-and-preferences)

</div>

## Download and install

1. Open the [latest release](https://github.com/Nightmare13123/OmniDocZ/releases/latest).
2. In **Assets**, download **`OmniDocZ-Setup-<version>.exe`**.
3. Run the installer and open **OmniDocZ**. Drag files into the app or use **Browse File** to get started. The interactive guide walks you through the main tools.

The installer includes what you need to run OmniDocZ on 64-bit Windows 10 or 11. Document processing runs on your PC, with no account or subscription required. Downloads and update checks use an internet connection.

| Release asset | What it gives you |
| --- | --- |
| `OmniDocZ-Setup-<version>.exe` | The Windows desktop application. Start here for a new installation or an update. |
| `ai_bundle.zip` | Optional local AI for scanned text recognition and automatic background removal. Select AI during setup when offered, or install it from the AI status indicator in the app. The AI tools run offline after installation. |
| `fonts_bundle_essential.zip` and `fonts_bundle_full.zip` | Optional typeface collections for document editing. Choose the Essential or Full bundle in setup or under **Get More** in the editor’s font menu. You can also add your own fonts. |

## PDFs and documents

### Edit text and build pages

- **Edit text on the page.** Turn on **Edit Text** and double-click a line or paragraph to correct it in place. OmniDocZ tries to match the existing font, size, color, and styling. Press **Enter** to apply changes or **Shift + Enter** to add a line where supported. Scanned pages use the optional OCR component.
- **Compose a document.** Start with a blank page or build on an existing file. Add formatted text, movable text boxes, images, hyperlinks, and editable tables. Resize and position elements on the page and export a table to XLSX.
- **Draw, highlight, and revise.** Use the pen and highlighter with adjustable color and thickness, erase strokes, and undo or redo edits. Rotate pages or adjust their dimensions using A4, Letter, Legal, square, or a custom size. Zoom from 40% to 250% with the on-screen controls or **Ctrl + mouse wheel**.

### Combine, organize, and extract

- **Merge different file types.** Load multiple PDFs, Word or OpenDocument files, spreadsheets, and images into one workspace. For example, put a Word cover, PDF agreement, formatted spreadsheet, and scanned receipts into one PDF.
- **Reorder at either level.** Move entire source files or arrange individual pages with thumbnail previews. Add blank pages, delete unwanted pages, and add files to the current workspace as you go.
- **Save only the pages you need.** In **Extractor & Splitter**, enter individual pages or ranges such as `1, 3, 5-8`, or select even pages, odd pages, or either half. Export the selection as a document, spreadsheet, or image, depending on the chosen format.

### Preview, optimize, and export

- **Fit a file-size limit.** Set a target in MB when the output supports it. Choose **Original**, **Balanced**, **High**, or **Ultra** quality. For PDFs, the app estimates the minimum achievable size and shows which quality levels fit the chosen limit.
- **Preview changes as you work.** Turn on **Live Preview** to see how color inversion, page numbers, and watermarks will look before you save.
- **Prepare consistent pages.** Add a text or logo watermark with adjustable opacity. Configure page numbers, headers, and footers, including position, format, font, starting number, and whether to skip the cover.

| Task | Formats and options |
| --- | --- |
| Open or combine documents | PDF, Word `.docx`, Writer `.odt`, Excel `.xlsx` and `.xls`, Calc `.ods`, `.csv`, PNG, JPEG, and WebP |
| Export documents or selected pages | PDF, archival PDF/A-1b option, DOCX, ODT, XLSX, ODS, PNG, and JPEG |
| Export tabular data | Extract detected PDF tables to XLSX, ODS, or CSV. Use **Extractor & Splitter** for CSV output from selected PDF pages. |

Output options vary by tool and by the type of content you open.

## Excel Studio (Beta)

Create or edit workbooks in the spreadsheet grid, then switch to **Docs Mode** to work with the print layout. Open XLSX, XLS, ODS, and CSV. Save a workbook as XLSX or ODS, or export the active sheet to CSV.

| In the grid | What you can do |
| --- | --- |
| **Workbooks and navigation** | Add, rename, duplicate, reorder, and color-code sheet tabs. Insert, delete, hide, and resize rows and columns. Freeze panes, zoom, jump to cells, and toggle gridlines or headings. |
| **Formulas and auditing** | Use AutoSum, a function assistant, and formulas such as `SUM`, `IF`, `COUNTIF`, and `VLOOKUP`. Show formulas and their precedents or dependents, and choose automatic or manual recalculation. |
| **Formatting** | Set fonts, colors, borders, alignment, and number formats. Wrap text, merge cells, and apply conditional formatting or data validation. |
| **Data cleanup and import** | Find and replace, sort with multiple keys, filter by value or condition, remove duplicates or empty rows, split text into columns, and convert numeric text to numbers. Import a CSV or PDF tables into sheets, or paste all, values only, or formats only. |
| **Charts and supporting details** | Create column, bar, line, and pie charts from selected data. Add cell comments, hyperlinks, and images. |
| **Print layout and PDF export** | Choose paper size, orientation, margins, and print area. Preview the active sheet or whole workbook, export to PDF, or use **Insert into Document** to bring data from the active sheet into an editable table. |

## OCR and text extraction

- **Make a scanned PDF searchable.** In **Text Extractor**, choose the searchable PDF tool to add a selectable text layer over the scanned pages. The exported PDF keeps its appearance while letting you search, select, and copy recognized text. Choose the European/Spanish or English-only profile, set the resolution from 150 to 450 DPI, and optionally enhance the image before recognition.
- **Copy text from part of a page.** Use **Extract Text** in the editor and draw a box around the text you want. Copy the result to the clipboard, or use **Edit Text** to correct recognized text in place.
- **Recover and reformat content.** Open a PDF, DOCX, ODT, or supported image in **Text Extractor**. Edit the extracted text with headings, bold, italics, and underline, then export it in the format you need.
- **Clean up a scan or photo.** Automatically detect page edges, crop, and correct perspective, adjust the four corners by hand, or straighten tilted content on its own.

OCR on scanned pages and images requires the optional AI component.

## Image tools

- **Preview images and PDF pages.** Browse the file queue and the pages of a PDF, zoom or view at actual size, and check image dimensions and file size.
- **Remove backgrounds.** Use the optional local AI on one or more images and save transparent PNGs. Choose from available background-removal models and optionally fill gaps in the result. Use the manual brush, selection, or crop tools for hands-on cleanup.
- **Turn images into outlines.** Generate line art for coloring or trace only the outside silhouette for a sticker, logo, or stencil. Save on a white background as JPEG or with transparency as PNG.
- **Lay out photos on A4.** Turn images or PDF pages into a printable album or contact sheet. Place 1, 2, 3, 4, 6, or 8 images per page, or let OmniDocZ arrange them automatically while preserving proportions.

## PDF security and forms

| Tool | What you can do |
| --- | --- |
| **Password protection** | Encrypt PDFs with AES-256. Set an opening password and configure permissions for printing, copying, and editing. Remove password protection using the current password. |
| **Permanent redaction** | Mark areas manually or find occurrences of a phrase. Apply redaction to remove the underlying content in the marked areas and save a redacted copy. |
| **Signatures** | Sign with a `.pfx` or `.p12` certificate (PAdES / PKCS#7), add a visible stamp or an image of a handwritten signature, or create a PDF signature field for later signing. |
| **Interactive forms** | Fill existing PDF form fields such as text boxes, checkboxes, and dropdowns. Save an editable copy or flatten the completed fields into the page. |
| **Metadata** | Review, change, or clear PDF fields such as title, author, subject, keywords, creator, and producer. |

## Batch processing and preferences

- **Process a queue in one run.** Apply output conversion, compression, a target size, page rotation, color inversion, numbering, or a watermark across multiple files. Apply AES-256 encryption when exporting PDFs. Choose this workflow when you want individual outputs from multiple source files.
- **Use the interface in your language.** Switch among English, Spanish, French, Portuguese, German, and Italian. In Settings you can replay the interactive guide, review or adjust recommended queue and page limits, and enable GPU acceleration for OCR or background removal on compatible hardware.
- **Manage updates and get help in the app.** Check for new versions, manage the AI component, reopen your last document, or send the developer a bug report or suggestion.

---

OmniDocZ is developed by **NightmareZDev** and is part of **NightmareZProtocol**. If the app helps with your work, you can [support its development on Ko-fi](https://ko-fi.com/nightmarezdev).
