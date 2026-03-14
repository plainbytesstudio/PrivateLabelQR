<p align="center">
  <img src="PrivateLabelQR.png" alt="Private Label QR" width="120"/>
</p>

<h1 align="center">Private Label QR</h1>

<p align="center">
  A privacy-first, native QR code &amp; barcode generator and label printer for Windows.<br/>
  Built for speed, simplicity, and professional output.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-blue?logo=windows" alt="Platform"/>
  <img src="https://img.shields.io/badge/.NET-8.0-purple?logo=dotnet" alt=".NET 8"/>
  <img src="https://img.shields.io/badge/network-100%25%20Offline-brightgreen?logo=shield" alt="100% Offline"/>
</p>

---

## 🔒 Privacy Commitment

> **Your data never leaves your machine.**

Private Label QR is designed with a **zero-trust architecture**:

- **No internet connection required** — works fully offline, no handshake, no DNS lookup
- **No telemetry, analytics, or tracking** of any kind
- **No cloud storage** — files are read and written only to paths you choose
- **No background services** — the app does nothing when you're not using it

Your QR content, imported spreadsheets, and exported files stay on your local machine. Always.

> *This is a free tool provided by PlainBytes Studio. We keep it closed-source to prevent low-quality clones, but we guarantee 100% privacy and local processing.*

---

## 🛡️ Security Verified

As an independent developer project, this application is **not digitally signed** with an EV certificate. However, the release binary has been scanned and verified clean by all major antivirus engines worldwide.

<p align="center">
  <strong>VirusTotal Result: 0 / 65 — Clean</strong><br/>
  <sub>Verified by Microsoft Defender, Kaspersky, BitDefender, Norton, ESET, Malwarebytes, Avast, and 65+ other engines.</sub>
</p>

<p align="center">
  <a href="https://www.virustotal.com/gui/file/b73a636ff9db67a0a53d00911c639b0527eab7e85eb54a3f70cda6bbd9136bfb">
    <img src="virustotal.png" alt="VirusTotal 0/65 Clean" width="700"/>
  </a><br/>
  <sub>Click the image to view the full VirusTotal report</sub>
</p>

---

## 📸 Screenshots

<p align="center">
  <img src="screenshot-single.jpg" alt="Single Mode" width="800"/><br/>
  <sub>Single Mode — Real-time QR / Barcode preview with color customization</sub>
</p>

<p align="center">
  <img src="screenshot-bulk.jpg" alt="Bulk Mode" width="800"/><br/>
  <sub>Bulk Mode — Import CSV/Excel, map columns, preview &amp; export label PDF</sub>
</p>

---

## ✨ Features

### 🏷️ Single Mode
- Generate QR codes in real time as you type
- Export as **PNG**, **JPG**, **SVG** (vector), or **EPS** (vector)

### 📊 Bulk Mode
- Import data from **CSV** or **Excel** files (drag-and-drop or click to browse)
- Map any column to QR/Barcode content and label text
- Live first-page PDF preview with loading indicator
- Export professional label sheets using industry-standard templates:

| Template | Paper | Grid | Label Size |
|----------|-------|------|------------|
| Avery 5160 | US Letter | 3 × 10 | 2.625″ × 1″ |
| Avery 5163 | US Letter | 2 × 5 | 4″ × 2″ |
| Avery L7160 | A4 | 3 × 7 | 63.5 × 38.1 mm |
| Thermal 2″×1″ | 2″ × 1″ | 1 × 1 | Single label (thermal printers) |

### 📐 Barcode Support
- **Code 128** — general-purpose barcode, recommended for asset tags and inventory
- **EAN-13** — retail product barcode with automatic check-digit calculation
- High-DPI rendering with Human Readable Text (HRT)
- Smart encoding selector: choose QR Code, Code 128, or EAN-13 from a single dropdown

### 🎨 Style Customization
- **Color Picker** — HSV color wheel with hex input, preset swatches, and optional alpha channel
- Adjust module size (auto-optimized when logo is present) and error correction level (L / M / Q / H)
- Overlay a custom logo at the center of QR codes
- **Radial Spotlight Preview** — design canvas with subtle grid lines and a radial gradient spotlight effect

### 🖥️ Interface
- Dark theme with custom title bar
- Responsive layout — fixed sidebar, scalable preview canvas
- Smooth debounced preview refresh
- Status bar with language switcher and real-time feedback

### 🌍 Internationalization
- 5 languages: English, 简体中文, Deutsch, Français, 日本語
- Language preference persisted across sessions

---

## 🚀 Quick Start

### Prerequisites

- Windows 10 / 11 (x64)
- [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.25-windows-x64-installer?cid=getdotnetcore) — download the latest **x64** installer from Microsoft if not already installed

### Download & Run

1. Download the latest **`PrivateLabelQR-v1.0.2-win-x64.zip`** from the Releases page
2. Extract the ZIP to a local folder
3. Run **`PrivateLabelQR.exe`**

> **💡 Windows SmartScreen Notice**
>
> Since this app is from an independent developer and is not digitally signed, Windows SmartScreen may show a warning on first launch. This is expected behavior for unsigned software — it does not indicate a security risk.
>
> To proceed: click **"More info"** → then click **"Run anyway"**.

<p align="center">
  <img src="demo-drag-drop.webp" alt="Drag & Drop Demo" width="720"/><br/>
  <sub>Drag an Excel file onto the canvas to instantly generate label previews</sub>
</p>

---

## 📋 Usage

1. **Single mode** — Type or paste content into Label + Content fields, customize style, export as image
2. **Bulk mode** — Drop a CSV/Excel file onto the canvas (or click to browse), map columns, export as label PDF
3. **Encoding** — Switch between QR Code, Code 128, and EAN-13; irrelevant controls hide automatically
4. **Style** — Adjust colors via the color picker, tune module size, error correction, and optional logo
5. **Output** — Choose format (image or PDF template) and click Export

---

<p align="center">
  <sub>Built with care for people who value privacy.</sub>
</p>
