# 🔍 PDFrint

> **PDF Fingerprinting Tool** — Extract cryptographic hashes from PDF files with a clean GUI.

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)

---

## 📌 Overview

**PDFrint** is a lightweight desktop application built with Python and Tkinter that lets you select any PDF file and instantly compute its cryptographic hash fingerprints. Useful for:

- ✅ File integrity verification
- ✅ Forensic document identification
- ✅ Detecting tampered or duplicate PDFs
- ✅ Comparing PDFs against known-file databases

---

## ✨ Features

- 📂 Simple GUI — browse and select any PDF in one click
- 🔐 Computes **5 hash algorithms** simultaneously:
  - MD5
  - SHA-1
  - SHA-256
  - SHA-512
  - SHA3-256
- 📋 Copy all results to clipboard instantly
- 📁 Displays file name and size alongside hashes
- ⚡ No internet connection required — fully offline
- 🪶 Zero external dependencies (pure Python standard library)

---

## 🖥️ Screenshot

```
┌─────────────────────────────────────────────┐
│  📂 Select PDF     report.pdf               │
│─────────────────────────────────────────────│
│  File: report.pdf                           │
│  Size: 204,800 bytes                        │
│  ──────────────────────────────────────     │
│  MD5:                                       │
│  d41d8cd98f00b204e9800998ecf8427e           │
│                                             │
│  SHA-1:                                     │
│  da39a3ee5e6b4b0d3255bfef95601890afd80709  │
│                                             │
│  SHA-256:                                   │
│  e3b0c44298fc1c149afb...                    │
│                                 📋 Copy     │
└─────────────────────────────────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Tkinter (included with standard Python installations)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/PDFrint.git
cd PDFrint
```

### Run

```bash
python pdf_hash_extractor.py
```

No `pip install` needed — PDFrint uses only Python's built-in libraries.

---

## 📖 Usage

1. Launch the app with `python pdf_hash_extractor.py`
2. Click **📂 Select PDF** and choose your PDF file
3. Hashes are computed and displayed instantly
4. Click **📋 Copy to Clipboard** to copy all results

---

## 🔐 Hash Algorithms

| Algorithm | Output Length | Use Case |
|-----------|--------------|----------|
| MD5       | 128-bit (32 hex chars) | Quick identity check |
| SHA-1     | 160-bit (40 hex chars) | Legacy compatibility |
| SHA-256   | 256-bit (64 hex chars) | Standard integrity verification |
| SHA-512   | 512-bit (128 hex chars) | High-security fingerprinting |
| SHA3-256  | 256-bit (64 hex chars) | Modern cryptographic standard |

---

## 📁 Project Structure

```
PDFrint/
├── pdf_hash_extractor.py   # Main application
└── README.md               # This file
```

---

## 🛠️ Built With

- [Python](https://www.python.org/) — Core language
- [Tkinter](https://docs.python.org/3/library/tkinter.html) — GUI framework
- [hashlib](https://docs.python.org/3/library/hashlib.html) — Hash computation

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<p align="center">Made with ❤️ using Python</p>
