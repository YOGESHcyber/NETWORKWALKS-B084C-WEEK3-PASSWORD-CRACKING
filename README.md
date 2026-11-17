# NETWORKWALKS-B084C-WEEK3-PASSWORD-CRACKING
"Week 3 Cybersecurity Internship – PDF Password Cracking and Hash Extraction using John the Ripper and Johnny GUI on Windows."

# WEEK 3 – PASSWORD CRACKING WITH JOHN THE RIPPER

### NETWORKWALKS CYBERSECURITY INTERNSHIP

| Field | Details |
|---|---|
| **Name** | YOGESHWARAN S |
| **Batch** | B084C |
| **Internship Organization** | NetworkWalks |
| **Internship Week** | Week 03 |
| **Domain** | Cybersecurity |
| **Project Title** | PDF Password Cracking |
| **Tools Used** | John the Ripper, Johnny GUI |
| **Operating System** | Windows |

---

## 1. Project Overview

This repository documents my Week 03 practical exercise on PDF password security using John the Ripper and Johnny GUI.

The objective was to understand PDF hash extraction, password auditing and dictionary-based password attacks.

## 2. Tools Used

- Windows 64-bit
- John the Ripper 1.9.0 Jumbo
- Johnny GUI
- Online PDF Hash Extractor
- Notepad
- PDF Viewer

## 3. Practical Implementation

### Step 1: Downloading John the Ripper

Downloaded John the Ripper 1.9.0 Jumbo for Windows 64-bit and extracted the files.

### Step 2: Configuring Johnny GUI

- Opened Johnny application.
- Navigated to Settings.
- Selected john.exe from the run folder.
- Successfully detected John the Ripper.

### Step 3: Extracting PDF Hash

- Selected My Locked PDF1.pdf.
- Uploaded the PDF to the PDF Hash Extractor.
- Extracted the PDF hash beginning with `$pdf$`.

### Step 4: Creating Hash File

- Opened Notepad.
- Pasted the extracted hash.
- Saved the file as hash1.txt.

### Step 5: Loading Hash File

- Opened Johnny.
- Selected Open password file.
- Loaded hash1.txt successfully.

### Step 6: Password Auditing

- Selected Start New Attack.
- Waited for the process to complete.
- Johnny displayed 100% completion.
- Result: 1 cracked, 0 left.

### Step 7: Password Verification

The recovered password will be tested against the original training PDF.

## 4. Results

| Task | Status |
|---|---|
| John the Ripper Installation | Completed |
| Johnny GUI Configuration | Completed |
| PDF Hash Extraction | Completed |
| Hash File Creation | Completed |
| Hash Loading | Completed |
| Password Auditing | 1 Cracked, 0 Left |

## 5. Key Learnings

1. Understanding PDF encryption.
2. Extracting PDF password hashes.
3. Configuring John the Ripper.
4. Using Johnny GUI.
5. Understanding dictionary attacks.
6. Learning password auditing techniques.

## 6.  Results
<img width="1365" height="715" alt="Detected JTR" src="https://github.com/user-attachments/assets/9a4c7d9f-6d63-4960-b78c-adf787be8f02" />
<img width="1365" height="715" alt="Output_1" src="https://github.com/user-attachments/assets/c7d6d1e8-dd15-4e06-8faf-b0a1db04f600" />
<img width="1352" height="562" alt="HASH_VALUE" src="https://github.com/user-attachments/assets/9859f2f5-8b74-474c-9fe2-e8e351120e61" />
<img width="1365" height="715" alt="PDF1_OUTPUT" src="https://github.com/user-attachments/assets/43c58d0e-05bd-4c25-b331-749dde03f2ce" />
<img width="1365" height="716" alt="NW_PM2" src="https://github.com/user-attachments/assets/3543ffcd-7256-45ca-81ae-b33d7ff5a493" />
<img width="1365" height="767" alt="NW_PM2_OUTPUT" src="https://github.com/user-attachments/assets/d3a887f1-782a-4cd8-83db-cc721d22aea3"/>

## 7. Conclusion

This practical provided hands-on experience with PDF hash extraction and password auditing using John the Ripper and Johnny GUI.

It helped me understand the importance of password strength and secure document protection.

## 8. Disclaimer

This practical was performed for educational purposes using an authorized training PDF.

### PROJECT DONE BY :
YOGESHWARAN S
LinkedIn : www.linkedin.com/in/yogeshwaran-s-1b2038386

