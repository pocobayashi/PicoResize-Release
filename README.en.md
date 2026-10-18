# ⚡ PicoResize

[日本語](README.md) | [English](README.en.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

---

**PicoResize** is a high-performance Windows desktop application that batch processes images (JPG, PNG, WebP, BMP, TIFF) and PDF documents with **automatic margin trimming**, **smart aspect-ratio fitting**, and **target size (MB) compression** in a 100% secure, offline local environment.

---

## 🌟 Key Features

1. **Automatic Margin Trimming (Auto Trim)**
   - Automatically detects and removes unwanted white margins and borders from photos, scanned images, and PDF pages.
2. **Orientation-Aware Smart Resizing (Aspect Ratio Preservation)**
   - Fits images into the specified bounding box (e.g., `[ 640 ] × [ 480 ]`):
     - **Horizontal Images (Width ≥ Height)**: Fits into Width × Height = `640 × 480` preserving aspect ratio.
     - **Vertical Images (Height > Width)**: Fits into Height × Width = `640 × 480` (Width 480 × Height 640) with automatic orientation flip.
3. **Target File Size Compression (MB)**
   - Automatically adjusts compression quality using binary search to ensure files stay under the target size (e.g., `0.5` MB) with minimal visual degradation.
4. **Automatic Duplicate File Renaming**
   - If a file with the same name already exists in the destination folder, automatically appends `(2)`, `(3)`, etc., preventing accidental overwrites.
5. **Seamless Batch Processing of Images & PDFs**
   - Drag and drop PDF files (first page rasterized at 300 DPI) and various image files into the same processing queue.
6. **Ultra-Low Memory Footprint (10–20 MB Stable)**
   - Employs Win32 working set trimming, UI virtualization, and idle memory reclaiming to maintain a tiny ~10 MB footprint.
7. **Complete 8-Language Localization**
   - 🌐 Supports Japanese, English, Simplified Chinese, Traditional Chinese, Korean, Spanish, German, and French with instant real-time switching.
8. **Velopack Automatic Updates**
   - Integrated with Velopack for seamless one-click differential updates.

---

## 🖥️ System Requirements
- **OS**: Windows 10 (version 2004 or later) / Windows 11 (x64)
- **Runtime**: Self-contained (no external .NET runtime required)

---

## 🚀 Getting Started
1. Set the aspect ratio dimensions (`Width × Height`), target size in MB, and output format (`JPEG / PNG / WebP`).
2. Drag and drop your images or PDF files into the drop area (or use the "Add Files" button).
3. Click "🚀 Resize & Save" and select the destination folder.
4. Once completed, a confirmation dialog appears with a one-click option to open the output folder.

---

## 📄 License
MIT License
