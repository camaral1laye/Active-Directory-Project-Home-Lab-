# Active-Directory-Project-Home-Lab-
 I'll guide you through the steps of setting up an Active Directory (home lab) that includes Splunk, Kali Linux &amp; Atomic Red Team. Explore how a domain environment works, learn how to ingest events to a SIEM and generate telemetry related to attacks seen in the wild to help you detect them in the future. 


📘 README.MD Outline:
Project Description

Goals

Tools Used

Architecture Diagram

How to Recreate This Lab

Attack Simulations

Detection Insights

Future Work

active-directory-homelab/
├── README.md
├── architecture/
│   └── topology-diagram.png
├── setup/
│   ├── ad-domain-controller.md
│   ├── splunk-install.md
│   ├── kali-linux-setup.md
│   ├── atomic-red-team-usage.md
│   └── raspberry-pi-config.md
├── telemetry/
│   ├── attack-simulations/
│   ├── logs/
│   └── detection-summaries.md
├── scripts/
│   ├── install-splunk.sh
│   ├── configure-ad.ps1
│   └── run-atomic-tests.ps1
└── notes/
    └── learning-journal.md
