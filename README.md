# 🌀 Macan Mystic Downloader  
### *Batch Video Downloader & Media Utility*  
**Part of the Macan Angkasa Ecosystem**

---

## 🧩 Overview  

**Macan Mystic Downloader** is a next-generation batch video downloading utility developed as part of the **Macan Angkasa Ecosystem**.  
Built using **PySide6 (Qt for Python)** and powered internally by the **Macan Engine**, it provides a clean, fast, and stable interface for managing multiple video downloads in one session.

Designed for both enthusiasts and professionals, Mystic Downloader simplifies large-scale media retrieval while maintaining an elegant, corporate-grade user experience.

---
## 📸 Screenshot
<img width="814" height="687" alt="image" src="https://github.com/user-attachments/assets/82aba222-e220-4e55-a0af-7c5a7c6be180" />


---

## 📝 Changelog v7.2.0
- Update framework


## 🚀 Key Features  

✅ **Batch URL Management**  
Paste multiple video URLs — each line represents one download task.  

✅ **Smart Folder Handling**  
Automatically creates and manages dedicated download directories within the user’s system.  

✅ **Integrated Video Converter**  
Quickly convert downloaded media via the built-in `VideoConverterDialog` (requires `video_convert.py`).  

✅ **System-Level Integration**  
Easily open your download directory, execute batch scripts, or trigger Macan Engine directly from the UI.  

✅ **Dark Themed Professional UI**  
Clean and responsive interface inspired by modern media suites, with a splash screen for polished startup transitions.

---

## 🧠 Technical Overview  

- **Framework:** PySide6 (Qt for Python)  
- **Language:** Python 3.10+  
- **Integration:** Macan Engine (binary backend)  
- **UI System:** QMainWindow / QWidget hierarchy  
- **Theme:** Custom dark mode stylesheet  

The application structure is modular — separating UI, engine calls, and conversion dialogs for maintainability and scalability across Macan Angkasa suites.

---

## 🏗️ Architecture Summary  


User Input (Batch URLs)
↓
Batch Manager → macan-engine backend → download pipeline
↓
Conversion Module (video_convert.py)
↓
Final Output Folder (~/Downloads/Macan Video Download)

---

## ⚙️ How to Use  

1. Paste one or more video URLs into the right text box (one URL per line).  
2. Click **💾 Save URL List** to save all entries to `batch_urls.txt`.  
3. Click **🚀 Run Downloader** to launch the Macan Engine console.  
4. (Optional) Use **🔧 Video Convert** to reformat downloaded files.  
5. Access all completed downloads easily with **📂 Open Download Folder**.  

---

## 🧭 System Requirements  

| Component | Minimum Specification |
|------------|------------------------|
| **OS** | Windows 10 or later |
| **Python** | 3.10+ (64-bit) |
| **Libraries** | PySide6, subprocess, os, sys |
| **Disk Space** | At least 1 GB free |


---

## 📦 Distribution  

**Macan Mystic Downloader** is distributed as a **binary-only application**, integrated with the Macan Angkasa ecosystem.  
While built on open Python technologies, it contains proprietary modules (UI frameworks, backend integration) that remain closed-source under the **Macan Angkasa Binary License (MABL)**.

---

## ⚖️ License  


Macan Angkasa Binary License (MABL)
Copyright (c) 2025 Danx Exodus
Permission is granted to use, distribute, and execute this binary
for personal or internal use. Redistribution of the source code
or reverse engineering of proprietary components is prohibited.
This software integrates components from yt-dlp (GPL)
via the Macan Engine framework. All GPL components retain their
original licensing and attribution.

---

## 🏢 About Macan Angkasa  

**Macan Angkasa** is an independent software ecosystem founded by **Danx Exodus**,  
focused on building intelligent, modular, and enterprise-grade desktop software through Python and Qt technologies.

From AI frameworks to multimedia engines, the ecosystem embodies innovation, integration, and independence —  
bridging creativity with engineering precision.

> *“Beyond automation — it’s engineering with personality.”*  
> — **Macan Angkasa**

---

**Danx Exodus — Founder & Lead Developer**  
*Macan Angkasa Ecosystem*  
> “Independent Software. Corporate-Grade Engineering.”
