### ONLYOFFICE

ONLYOFFICE Document Server is a free collaborative online office suite comprising viewers and editors for texts, spreadsheets and presentations, fully compatible with Office Open XML formats: .docx, .xlsx, .pptx and enabling collaborative editing in real time.

Website: https://www.onlyoffice.com/

Github: https://github.com/ONLYOFFICE/

Document Server CORE - https://github.com/ONLYOFFICE/core

Document Server SERVER - https://github.com/ONLYOFFICE/server

CVE ID | Score | Description
-------|-------|-------------
[CVE-2021-25829](CVE-2021-25829) | **7.5 HIGH** | An improper binary stream data handling issue was found in the \[core\] module of ONLYOFFICE DocumentServer v4.0.0-9-v5.6.3. Using this bug, an attacker is able to produce a denial of service attack that can eventually shut down the target server.
[CVE-2021-25830](CVE-2021-25830) | **9.8 CRITICAL** | A file extension handling issue was found in \[core\] module of ONLYOFFICE DocumentServer v4.2.0.236-v5.6.4.13. An attacker must request the conversion of the crafted file from DOCT into DOCX format. Using the chain of two other bugs related to improper string handling, an attacker can achieve remote code execution on DocumentServer.
[CVE-2021-25831](CVE-2021-25831) | **9.8 CRITICAL** | A file extension handling issue was found in \[core\] module of ONLYOFFICE DocumentServer v4.0.0-9-v5.6.3. An attacker must request the conversion of the crafted file from PPTT into PPTX format. Using the chain of two other bugs related to improper string handling, a remote attacker can obtain remote code execution on DocumentServer.
[CVE-2021-25832](CVE-2021-25832) | **9.8 CRITICAL** | A heap buffer overflow vulnerability inside of BMP image processing was found at \[core\] module of ONLYOFFICE DocumentServer v4.0.0-9-v6.0.0. Using this vulnerability, an attacker is able to gain remote code executions on DocumentServer.
[CVE-2021-25833](CVE-2021-25833) | **9.8 CRITICAL** | A file extension handling issue was found in \[server\] module of ONLYOFFICE DocumentServer v4.2.0.71-v5.6.0.21. The file extension is controlled by an attacker through the request data and leads to arbitrary file overwriting. Using this vulnerability, a remote attacker can obtain remote code execution on DocumentServer.
CVE-2023-30186 | **9.8 CRITICAL** | A use after free issue discovered in ONLYOFFICE DocumentServer 4.0.3 through 7.3.2 allows remote attackers to run arbitrary code via crafted JavaScript file.
CVE-2023-30187 | **9.8 CRITICAL** | An out-of-bounds memory access vulnerability in ONLYOFFICE DocumentServer 4.0.3 through 7.3.2 allows remote attackers to run arbitrary code via crafted JavaScript file.
CVE-2023-30188 | **7.5 HIGH** | Memory Exhaustion vulnerability in ONLYOFFICE Document Server 4.0.3 through 7.3.2 allows remote attackers to cause a denial of service via crafted JavaScript file.
