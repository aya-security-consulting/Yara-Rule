# YARA Rules Repository

A curated repository of **YARA detection rules** designed to support **malware analysis, threat hunting, file triage, incident response, and forensic investigations**.

## Overview

This repository centralizes YARA rules intended to help defenders identify malicious files, suspicious artifacts, malware families, offensive tooling, and unusual file patterns across endpoints, servers, storage systems, malware sandboxes, and forensic collections.

The objective is to provide a structured and reusable detection library that can be leveraged during malware triage, DFIR investigations, retro-hunting, and validation activities.

## What You Will Find

This repository contains YARA rules covering a wide range of defensive use cases, including:

- Malware family identification
- Webshell detection
- Offensive tool detection
- Packed and obfuscated file hunting
- Suspicious script detection
- Document-based threat detection
- Ransomware-related artifacts
- Credential theft tooling
- Persistence-related files
- Threat actor tooling patterns
- Generic suspicious indicators
- Sandbox and validation rules

## Purpose

The goal of this project is to make YARA content easier to access, review, maintain, and operationalize.

Each rule is intended to help security teams:

- Detect malicious or suspicious files
- Support malware triage
- Accelerate forensic analysis
- Improve retro-hunting capability
- Enrich detection engineering practices
- Validate file-based monitoring coverage

## Target Audience

This repository is intended for:

- SOC analysts
- Threat hunters
- DFIR analysts
- Incident responders
- Malware analysts
- Detection engineers
- Blue team practitioners

## Repository Structure

The content can be organized by malware family, file type, use case, or detection objective.

Example structure:

```text
yara_rules/
├── Malware/
├── Webshells/
├── Ransomware/
├── Loaders/
├── Credential_Access/
├── Scripts/
├── Documents/
├── Packers_Obfuscation/
├── Offensive_Tools/
├── Persistence/
├── Generic_Suspicious/
├── Threat_Actor_Tools/
├── Sandbox_Validation/
└── Deprecated/
