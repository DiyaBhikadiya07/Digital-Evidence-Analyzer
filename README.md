# 🔐 Digital Evidence Analyzer

<p align="center">
  <b>🕵️ A simple Python tool for analyzing digital files and extracting useful file information.</b>
</p>

---

## 📌 About The Project

**Digital Evidence Analyzer** is a Python-based tool that helps analyze different types of files and provides useful information about them.

The tool checks basic file details, timestamps, hidden files, suspicious extensions, file signatures, image metadata, PDF information, and ZIP file contents. 🔍

---

## ✨ Features

- 📄 **File Information** – Name, extension & file size
- 🕒 **Time Analysis** – Created, modified & accessed time
- 👻 **Hidden File Detection**
- ⚠️ **Suspicious Extension Detection**
- 🔍 **File Signature Analysis**
- 🖼️ **Image Analysis** – Width, height, format & metadata
- 📑 **PDF Analysis** – Pages, encryption & metadata
- 📦 **ZIP Analysis** – Files inside ZIP & password protection check

---

## 🛠️ Technologies Used

- 🐍 **Python**
- 🖼️ **Pillow** – Image analysis & metadata
- 📑 **PyPDF2** – PDF analysis
- 📦 **ZipFile** – ZIP file analysis
- 💻 **OS Module** – File information & timestamps

---

## 🚀 How To Run

### 1️⃣ Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL

2️⃣ Install Required Libraries
pip install Pillow PyPDF2
3️⃣ Run the Project
python dft_kit.py
4️⃣ Enter File Path

The program will ask for the file path:

Enter File Path:

Enter the path of the file you want to analyze. 🔎

📂 Supported File Analysis
File Type	Analysis
🖼️ JPG / JPEG / PNG	Image details & metadata
📄 PDF	Pages, encryption & metadata
📦 ZIP	Files & password protection
📁 Other Files	Basic file information
🔍 What It Checks

The analyzer can identify:

File name
File extension
File size
Created time
Modified time
Accessed time
Hidden file status
Suspicious extensions
Multiple file extensions
File magic bytes / signature

🎯 Project Purpose

This project was created to understand the basics of digital file analysis and metadata extraction using Python.

It is a simple project for learning how different file types can be inspected programmatically. 🐍🔍



⭐ If you find this project useful, consider giving it a Star!
