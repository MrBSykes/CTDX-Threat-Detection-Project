# 🔐 CTDX Threat Detection Project
**SOC Investigation Simulation | Cyber Job X (SCIPP)**
**Completed: March 2026**

---

## 📌 Overview

This project simulates a real-world Security Operations Center (SOC) investigation, focusing on detecting and analyzing suspicious activity within a controlled lab environment.

The objective was to identify hidden data, analyze system artifacts, and apply forensic techniques to uncover potential indicators of compromise (IOCs).

---

## 🎯 Objectives

- Perform forensic analysis on a suspicious file
- Detect hidden or obfuscated data
- Extract and decrypt embedded content
- Document findings in a structured investigation report

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| ExifTool | Metadata analysis |
| Steghide | Hidden data extraction |
| GPG | Decryption & key handling |
| CyberChef | Data decoding & transformation |
| Linux CLI | Investigation workflow |

---

## 🔍 Investigation Workflow

### 1. Initial Analysis
- Examined `challenge.jpg` for suspicious behavior
- Identified anomalies suggesting hidden content

### 2. Metadata Extraction
- Used `ExifTool` to extract metadata
- Detected irregular fields indicating possible steganography

### 3. Steganography Detection
- Used `Steghide` to analyze and extract hidden data
- Successfully recovered an embedded key

### 4. Decryption Process
- Applied `GPG` to decrypt extracted content
- Recovered hidden message from encrypted payload

### 5. Data Validation
- Used `CyberChef` to decode and verify extracted data
- Cross-validated findings across multiple tools

---

## 🚨 Key Findings

- Image file contained hidden embedded data
- Successfully extracted a secret key
- Payload was encrypted and required decryption
- Confirmed use of data obfuscation techniques

---

## 🧠 Skills Demonstrated

- Digital Forensics
- Threat Detection & Analysis
- Steganography Techniques
- Metadata Analysis
- Encryption/Decryption (GPG)
- SOC Investigation Workflow

---

## ⚠️ Challenges

- Delay due to missing project file (`challenge.jpg`)
- Required iterative analysis across multiple tools
- Ensuring validation of findings at each stage

---

## ✅ Outcome

Successfully completed a full forensic investigation cycle, identifying hidden data and producing a structured SOC-style report.

---

## 📂 Repository Structure

```
CTDX-Threat-Detection-Project/
│
├── README.md
├── report/
│   └── investigation-report.md
├── evidence/
│   ├── metadata-output.txt
│   └── extracted-data.txt
├── screenshots/
│   ├── exiftool-output.png
│   ├── steghide-process.png
│   ├── gpg-decryption.png
│   └── cyberchef-analysis.png
```
