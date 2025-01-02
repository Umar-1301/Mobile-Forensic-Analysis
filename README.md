# Mobile Device Forensics: Analysis Scenario

This repository showcases my forensic analysis of a mobile device, conducted as part of an academic project for the Mobile Device Forensics module (CMP6186) at Birmingham City University. The project involves analyzing raw and extracted data to investigate alleged intellectual property theft.

---

## **Project Overview**

The investigation focused on:
- **Proving or disproving** the alleged criminal offense.
- Identifying **other parties involved** in the activity.
- Determining the **suspects’ intentions** and gathering supporting evidence.

### **Deliverables**
1. **Streamlined Forensic Report (MG22B SFR1)**: A professional summary for authorities.
2. **Contemporaneous Notes**: Detailed logs of the investigation, methodologies, and findings.

---

## **Scenario**
The alleged offense involved theft of company IP regarding a prototype teddy bear, codenamed **Porsche**, by a suspect named Ross. A seized mobile device was analyzed to provide evidence regarding:
- Ownership of the device.
- Key communications and activities on the device.
- Evidence of criminal intent or further plans.

---

## **Tools Used**
1. **Cellebrite Reader**: For forensic extraction and visualization.
2. **RabbitHole v2.2.5.0**: For parsing and interpreting structured data.
3. **Autopsy**: File system analysis for uncovering hidden or deleted files.
4. **HxD / WinHex**: Hexadecimal analysis of raw data for low-level insights.

---

## **Key Findings**
### **Attribution of Mobile Device**
- Identified the owner using metadata, login credentials, and device settings.

### **Communication Analysis**
- Group conversations analyzed to identify:
  - Participants, timestamps, and first image shared.
  - Betrayal messages and associated timestamps.

### **Search and Activity Logs**
- Searches for "Vitality Blast" and "Amsterdam" with timestamps recovered.
- Login credentials and usage details of various applications.

### **Evidence of Criminal Intent**
- Discovered plans for further criminal activities based on app usage and logs.

---

## **Repository Contents**
- **MG22B_SFR1_Report.pdf**: The Streamlined Forensic Report.
- **contemporaneous-notes/**:
  - `notes.md`: Step-by-step examination process and findings.
  - `screenshots/`: Supporting visual evidence from the analysis.
- **evidence/**: Raw data files and extracted UFDR report.
- **tools/**: Forensic tools used in the project.
- **LICENSE**: Open-source license for the repository.

---

## **How to Use**
1. View the **MG22B SFR1 Report** for the investigation summary.
2. Explore **contemporaneous-notes/** for detailed methodology and evidence.
3. Use the tools in the repository to replicate the analysis (where applicable).

---

## **Acknowledgments**
This project was completed using resources and templates provided by Birmingham City University for educational purposes.

---
