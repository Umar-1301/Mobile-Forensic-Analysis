# Mobile Device Forensics: Analysis Scenario

This repository contains two key deliverables from a forensic investigation conducted as part of the **Mobile Device Forensics (CMP6186)** module at Birmingham City University:
1. **Streamlined Forensic Report (SFR1)**: A formal report summarizing the investigation findings.
2. **Contemporaneous Notes**: Detailed documentation of the forensic process, including methodologies, tools used, and evidence analysis.

---

## **Key Findings**

### Attribution of Device Ownership
- The mobile device, a Samsung Galaxy A3 (2017), was confirmed to belong to **Ross Geller** through metadata and user accounts analysis.

### Analysis of Group Communication
- Identified a WhatsApp group named **"Big Bears"**, created on **03/09/2019**, which discussed the intellectual property (IP) theft. Key participants included Ross, Janice, and others.
- Found evidence that **Ross and Janice** conspired to steal and sell the prototype design of a teddy bear, codenamed **Porche**, to a buyer associated with **Vitality Blast**.

### Email Evidence
- Emails between Ross and Janice highlighted their intentions to:
  - Steal the Porche patent.
  - Book flights to Amsterdam for a handover.
- Ross's email account was used for further communication with unidentified group members, likely related to the theft.

### Web Data and Flight Confirmation
- Ross searched for information on **Vitality Blast** and booked flights to Amsterdam using **lastminute.com**, confirmed through raw data and login credentials.
- A file named **FlightConfirmed.txt** detailed a flight on **06/09/2019 at 04:45:00**, solidifying the plan's timeline.

### Additional Criminal Intentions
- Evidence from Samsung Notes revealed plans by Ross to clone Janice’s credit card, steal her money, and escape to a "non-extradition" country under her name.

---

## **Tools and Methodologies**

### Tools Used
1. **Cellebrite Reader**: For analyzing UFDR files and extracting key evidence.
2. **Autopsy**: Conducted raw file system analysis to recover hidden and deleted data.
3. **Rabbit Hole v2.2.5.0**: Parsed databases and email content for deeper insights.
4. **HxD**: Used for hexadecimal analysis of raw binary data.

### Methodology
- Extracted and analyzed UFDR files and raw file system data.
- Maintained detailed **contemporaneous notes** to ensure reproducibility and accuracy.
- Correlated evidence from multiple sources (e.g., messages, emails, web data) to form a comprehensive narrative.

---
