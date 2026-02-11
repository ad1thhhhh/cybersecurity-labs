# Case 001 – Disk Forensic Investigation

## Case Overview

A forensic analysis was conducted on a disk image as part of an investigation involving suspected financial misconduct and coordinated activities between multiple actors.

The objective of this analysis was to identify and recover relevant digital evidence that may support the investigation team.

---

## Tools Used

- FTK Imager

---

## Key Findings

### 1. Recovered Financial Records

- A password-protected ZIP archive was discovered.
- The archive contained an Excel spreadsheet summarizing bank transactions.
- The spreadsheet is found to be a password protected file.

This data may indicate financial movements relevant to the investigation.

<img width="1418" height="727" alt="image" src="https://github.com/user-attachments/assets/86c89244-7847-49f5-b8bc-8a0554ea91a4" />


---

### 2. Email Correspondence Between Actors

Email communications between "George" and "Martha" were recovered and examined.

The content of the emails suggests:
- Coordination between involved parties
- Evidence of intent
- References to financial activities

<img width="1553" height="868" alt="image" src="https://github.com/user-attachments/assets/d97794f0-5993-46d1-ad94-002010bbe379" />
<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/34d3b274-0f2a-499d-87f0-4926482685a4" />

---

### 3. Credential Information Recovered

Password-related details were identified during the examination.

<img width="1190" height="661" alt="image" src="https://github.com/user-attachments/assets/543398bd-34be-4ede-87ff-1c3407c9f217" />


---

## Forensic Methodology

1. The disk image was loaded into FTK.
2. File system artifacts were indexed.
3. Email artifacts were extracted and analyzed.
4. Archive files were identified and examined.
5. Relevant documents were recovered and documented.
6. Evidence was preserved in accordance with forensic best practices.

---

## Evidence Handling Notes

- All analysis was conducted on a forensic image.
- Original evidence integrity was preserved.
- Findings were documented through screenshots and exported reports.
- An official FTK-generated report was created for investigative use.

---

## Conclusion

The forensic examination successfully recovered financial records, email communications, and credential-related data that may be of significant interest to the investigation team.

The findings suggest potential coordination and financial activity linked to the actors involved.

Further analysis of transaction timelines and communication metadata is recommended.
