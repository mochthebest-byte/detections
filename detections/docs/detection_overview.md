# Detection Overview

This repository contains SOC-focused detection rules designed for
credential abuse, lateral movement, and anomalous authentication.

## Covered Scenarios

### Linux
- SSH brute-force followed by successful login
- Internal lateral movement via SSH

### Cloud
- Rare or anomalous successful login

## Design Principles
- Behavior-based detection over static thresholds
- Explicit false-positive documentation
- MITRE ATT&CK mapping
- SOC-ready response actions

## Intended Audience
- SOC Tier 1 / Tier 2
- Detection Engineering
- Blue Team Analysts

## Notes
These rules are designed for learning, tuning, and interview demonstration
purposes and should be adapted before production use.
