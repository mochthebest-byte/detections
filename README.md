# Detections

This repository contains SOC-focused detection rules for authentication abuse,
credential compromise, and lateral movement scenarios.

The goal of this project is to demonstrate practical detection engineering
skills, including threat modeling, MITRE ATT&CK mapping, and detection tuning.

## 📁 Repository Structure

detections/
├── linux/
│ ├── ssh_bruteforce_success.yml
│ └── lateral_movement.yml
├── cloud/
│ └── rare_login.yml
├── docs/
│ └── detection_overview.md
└── CHANGELOG.md


## 🔍 Covered Detection Scenarios

### Linux
- SSH brute-force followed by successful login
- Suspicious internal SSH lateral movement

### Cloud
- Rare or anomalous successful login

## 🧠 Detection Design Principles

- Behavior-based detection instead of single indicators
- Explicit documentation of false positives
- Clear SOC response actions
- MITRE ATT&CK technique mapping

## 🎯 Intended Audience

- SOC Tier 1 / Tier 2 analysts
- Blue Team engineers
- Detection engineering learners

## ⚠️ Disclaimer

These detection rules are created for learning and demonstration purposes.
They should be tuned and validated before use in production environments.
