<p align="center"><img src="icon.svg" width="120" alt="UPang-OES Runbook icon"></p>

# UPang-OES Production Outage Recovery Runbook

![Document ID](https://img.shields.io/badge/ID-IT--RUNBOOK--001-blue)
![Version](https://img.shields.io/badge/version-1.0-green)
![Pages](https://img.shields.io/badge/pages-18-lightgrey)
![Use](https://img.shields.io/badge/use-internal-red)

> When a University enrollment system goes down at 2 AM and the senior admin can't be reached, this runbook gets it back up safely. It's written so a junior IT engineer can follow it from first alert to closing the incident.

## 📥 Download

| Option | Link |
| --- | --- |
| **Read in the repo** | [`runbook.pdf`](https://github.com/fpaulpalis/outage/blob/main/runbook.pdf) |
| **Download a release** | [Releases](https://github.com/fpaulpalis/outage/releases) |

## 📖 What's Inside (18 pages)

- **Incident declaration:** how to declare a SEV-1, who takes which role, and who to escalate to
- **Troubleshooting, outside in:** DNS → network → server → app → database → logs → recent changes
- **Recovery actions:** what to do, a "do not do" list, and steps for database restore and failover
- **Verification:** recovery checks, a 45-minute monitoring window, and message templates for stakeholders
- **Worked example:** a 2:00 AM scenario with its timeline and post-incident review
- **Quick Card (p. 17):** a one-page summary to print and keep at the desk

## 🚦 How to Use

1. Open the PDF the moment a SEV-1 alert fires.
2. Declare the incident and assign roles (see the incident declaration section).
3. Work the troubleshooting checklist from the outside in.
4. Apply recovery actions, and check the "do not do" list before touching anything.
5. Run the recovery checks, then watch the system for 45 minutes.
6. Send stakeholder updates using the provided templates.
7. Close the incident and complete the post-incident review.

> 💡 **Tip:** Print the Quick Card (page 17) and keep it at your desk.

## ⚠️ Before You Use This

The values shown in **blue** are **examples only**. Replace them with your real production details (hosts, contacts, credentials locations, escalation paths) **before** relying on this runbook in a live incident.

## 📄 Document Info

| | |
| --- | --- |
| **Title** | UPang-OES Production Outage Recovery Runbook |
| **Document ID** | IT-RUNBOOK-001 |
| **Version** | 1.0 |
| **Classification** | Internal Use |
| **Audience** | Junior IT engineers, on-call staff |

## 🤝 Contributing

Found something outdated or unclear? Open an [issue](https://github.com/fpaulpalis/outage/issues) or submit a pull request. Please keep the document ID and bump the version number when updating the runbook.
