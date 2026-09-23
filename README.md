# DFIR Study Notes

Exam-style Digital Forensics & Incident Response study notes (detection / artifacts focus).

## Browse in the browser

Open [`index.html`](index.html) locally, or use GitHub Pages once enabled:

**https://tommyt852.github.io/dfir-study-notes/**

| Page | Topic |
|------|--------|
| [Overview](overview.html) | Full outline + prove-X map |
| [01 Malware analysis](01-malware-analysis.html) | Static / dynamic / C2 |
| [02 Triage collection](02-triage-collection.html) | Velociraptor + KAPE |
| [03 Credential dumping](03-credential-dumping.html) | Detection only |
| [04 Persistence](04-persistence.html) | Services, tasks, WMI, Run keys |
| [05 Memory forensics](05-memory-forensics.html) | malfind, pslist vs psscan |
| [06 Data exfiltration](06-data-exfiltration.html) | Staging, rclone, DNS tunnel |
| [07 Web logs](07-web-logs.html) | Apache / IIS / web shells |
| [08 Incident response](08-incident-response.html) | NIST lifecycle |
| [10 Lab cheat sheet](10-lab-cheat-sheet.html) | Exam cards + lab screenshots |

Each topic page includes a short **Lab takeaways** box (Event IDs / tools / prove-X from classroom labs). Full lab packs are not published here.

## PDF downloads

All PDFs: [`pdfs/`](pdfs/) — including [`09-lab-takeaways.pdf`](pdfs/09-lab-takeaways.pdf) and [`10-lab-cheat-sheet.pdf`](pdfs/10-lab-cheat-sheet.pdf).

## Safety

Credential dumping and related tooling are documented only as **what to detect** and **which artifacts prove activity**. No attack how-tos.
